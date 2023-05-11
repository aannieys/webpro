# TicketBoo

## Group Member
* Miss Suphavadee Cheng 6488120
* Miss Ponnapassorn Iamborisut 6488179
* Miss Thadeeya Duangkaew 6488181
* Miss Ravikarn Jarungjitvittawas 6488210

How to run our program </br>
 </br>
1. First, you Download "sec1_gr10_pj2_ID120_179_181_210.zip"  </br>
2. Second, extract the "sec1_gr10_pj2_ID120_179_181_210.zip" file to "sec1_gr10_pj2_ID120_179_181_210" folder </br>
3. Third, you have to open "sec1_gr10_pj2_ID120_179_181_210" folder in Visual Studio Code </br>
4. Fourth, you open "sec1_gr10_pj2_ID120_179_181_210" folder, you have to click the "Terminal" button ad select "New Terminal" </br>
    and click the "Terminal" button again ad select "Split Terminal"  </br>
    ** (To open two terminal because we have to run two PORT at the same time) ** </br>
5. Fifth, the first Terminal, you should press command "$ cd sec1_gr10_src" </br>
          the second Terminal, you should press command "$ cd sec1_gr10_ws_src" </br>
    ** cd is to change directory (access in each folder) ** </br>
6. Sixth, first Terminal ['sec1_gr10_src' folder] you should press command "$ npm init"</br>
                                                                     ( change scripts in package.json from test to start 
                                                                           ```     "scripts": {
                                                                                    "start": "nodemon frontend.js"
                                                                                },)
                                                                            "$ npm install express"
                                                                            "$ npm install nodemon"
                                                                          ```
          second Terminal ['sec1_gr10_ws_src' folder] you should press command "$ npm init"
                                                                        ( change scripts in package.json from test to start 
                                                                              ```  "scripts": {
                                                                                    "start": "nodemon backend.js"
                                                                                },)
                                                                                "$ npm install express"
                                                                                "$ npm install nodemon"
                                                                                "$ npm install mysql2"
                                                                                "$ npm install dotenv"
                                                                                  ```
7. Seventh, Before you start you should open 'MYSQLWorkbench' and run the 'sec1_gr10_database.sql' </br>
    After that, you click 'Administration' and then click 'Users and Privileges'. </br>
    In addition, you should click 'Add Account' and fill the form of MYSQL_HOST, MYSQL_USERNAME, and MYSQL_PASSWORD [for the MYSQL_DATABASE = ticketboo] </br>
    Then, press 'Schema Privileges' and click 'Add Entry' then choose 'Selected schema of ticketboo'. </br>
    For the Object Rights, you should select 'SELECT, INSERT, UPDATE, DELETE' and Click "Apply" </br>
 </br>
    and change name of [MYSQL_HOST, MYSQL_USERNAME, and MYSQL_PASSWORD] that you create your account in the 'MYSQLWorkbench'  </br>
    and fill it in'.env' file to connect the database with web services. </br>
 </br>
8. Eighth, after you init, install all of frameworks, and connect the database in '.env' file. </br>
    You press command "$ npm start" in both of two Terminal to run all source code and all web service source code file. </br>
9. Ninth, when the first terminal [sec1_gr10_src] in console log returned: </br>

                                        > frontend@1.0.0 start</br>
                                        > nodemon frontend.js</br></br>

                                        [nodemon] 2.0.22</br>
                                        [nodemon] to restart at any time, enter `rs`</br>
                                        [nodemon] watching path(s): *.*</br>
                                        [nodemon] watching extensions: js,mjs,json</br>
                                        [nodemon] starting `node frontend.js`</br>
                                        Server listening at Port 3000</br></br>

and second terminal [sec1_gr10_ws_src] in console log returned:</br>

                                        > backend@1.0.0 start</br>
                                        > nodemon backend.js</br></br>

                                        [nodemon] 2.0.22</br>
                                        [nodemon] to restart at any time, enter `rs`</br>
                                        [nodemon] watching path(s): *.*</br>
                                        [nodemon] watching extensions: js,mjs,json</br>
                                        [nodemon] starting `node backend.js`</br>
                                        Server listening at Port 3030</br>
                                        Connected DB: ticketboo</br></br>


10. Tenth, you open the 'Google Chrome' and press 'http://localhost:3000/' then you will see the Home page. </br>
11. Eleventh, to go to the management page you have to press people button on the Nav bar in the right hand side </br>
    and login to see our page. If you did not have an account yet, you press sign up to register your account. </br>
    Then, Login again to see management page. </br>
12. Twelfth, When you already login you will see the Product-management page first. </br>
    To see the content you have to click 'search' the all concert will append in this page that you can edit or delete. </br>
    For add product, we have 'Add product' button for you to fill the the form and then refresh the page and click the search </br>
    it will append. </br>
 </br>
    For user-account-management you can click it in the nav bar. </br>
    To see the content you have to click 'search' the all User will append in this page that you can edit or delete. </br>
    For add user, we have 'Add user' button for you to fill the the form and then refresh the page and click the search </br>
    it will append. </br>
 </br>
13. Thirteenth, For another website's API, our group use API of Google Map. </br>
    The Google Map API is appear in each detail page. When you click the 'Concert & Entertainment' in the first nav. </br>
    When you click the card below the 'Concert & Entertainment' title, it will appear the detail of content and we embedded the Google Map API in each detail page. </br>
 </br>
:::::::::::::::::::::::::THANK YOU:::::::::::::::::::::::::
