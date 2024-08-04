<table><tr><td> <em>Assignment: </em> IT202 Milestone 2 Shop Project</td></tr>
<tr><td> <em>Student: </em> Meekat Hadi (mh82)</td></tr>
<tr><td> <em>Generated: </em> 8/4/2024 2:18:40 AM</td></tr>
<tr><td> <em>Grading Link: </em> <a rel="noreferrer noopener" href="https://learn.ethereallab.app/homework/IT202-AR451-M2024/it202-milestone-2-shop-project/grade/mh82" target="_blank">Grading</a></td></tr></table>
<table><tr><td> <em>Instructions: </em> <ol><li>Checkout Milestone2 branch</li><li>Create a new markdown file called milestone2.md</li><li>git add/commit/push immediate</li><li>Fill in the below deliverables</li><li>At the end copy the markdown and paste it into milestone2.md</li><li>Add/commit/push the changes to Milestone2</li><li>PR Milestone2 to dev and verify</li><li>PR dev to prod and verify</li><li>Checkout dev locally and pull changes to get ready for Milestone 3</li><li>Submit the direct link to this new milestone2.md file from your GitHub prod branch to Canvas</li></ol><p>Note: Ensure all images appear properly on github and everywhere else. Images are only accepted from dev or prod, not local host. All website links must be from prod (you can assume/infer this by getting your dev URL and changing dev to prod).</p></td></tr></table>
<table><tr><td> <em>Deliverable 1: </em> Users with admin or shop owner will be able to add products </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="https://user-images.githubusercontent.com/54863474/211707773-e6aef7cb-d5b2-4053-bbb1-b09fc609041e.png"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Add screenshot of admin create item page</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fmh82%2F2024-08-02T19.31.10admin%20create%20item%20page.jpg.webp?alt=media&token=fd7cf841-690e-4719-a0a9-b0438087d3dd"/></td></tr>
<tr><td> <em>Caption:</em> <p>Admin page of item creation screenshot with heroku URL<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Add screenshot of populated Products table clearly showing the columns</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fmh82%2F2024-08-02T19.32.28populated%20products%20table.jpg.webp?alt=media&token=ebb09221-ef61-4441-ab03-67379e9f6d35"/></td></tr>
<tr><td> <em>Caption:</em> <p>Products table with new item filled from VSCode<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 3: </em> Briefly describe the code flow for creating a Product</td></tr>
<tr><td> <em>Response:</em> <p>A form is used to collect data where the beginning utilizes the get_columns{}<br>helper function that creates the columns in the table. Some fields are auto<br>generated but each field is looped within the columns which are displayed to<br>the user. After the user fills out the data into the forms and<br>eventually submitted, the function save_data{} helper is retrieved which retrieves the table name<br>and post request which is converted into arguments and then uses the array_filter<br>function to create columns in the table. The array_map function then inserts the<br>user values into the columns where eventually the columns are mapped to the<br>placeholder where the INSERT command is executed into the table. This process is<br>completed once the ID of the latest product where it is displayed using<br>a flashing message.<br></p><br></td></tr>
<tr><td> <em>Sub-Task 4: </em> Add related pull request link(s)</td></tr>
<tr><td> <a rel="noreferrer noopener" target="_blank" href="https://github.com/ItsMeek23/mh82-IT202-451/pull/16#issuecomment-2266047292">https://github.com/ItsMeek23/mh82-IT202-451/pull/16#issuecomment-2266047292</a> </td></tr>
<tr><td> <em>Sub-Task 5: </em> Add a direct link to heroku prod for this file</td></tr>
<tr><td> <a rel="noreferrer noopener" target="_blank" href="https://mh82-prod.herokuapp.com/project/login.php">https://mh82-prod.herokuapp.com/project/login.php</a> </td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 2: </em> Any user can see visible products on the Shop Page </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="https://user-images.githubusercontent.com/54863474/211707773-e6aef7cb-d5b2-4053-bbb1-b09fc609041e.png"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Add a screenshot of the Shop page showing 10 items without filters/sorting applied</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fmh82%2F2024-08-02T20.36.37shop%20page%20showing%2010%20items.jpg.webp?alt=media&token=e765a42b-3f7b-4ab0-854d-a4315f66a725"/></td></tr>
<tr><td> <em>Caption:</em> <p>10 items of the shop page with heroku URL<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Add a screenshot of the Shop page showing both filters and a different sorting applied (should be more than 1 sample product)</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fmh82%2F2024-08-02T20.39.07shop%20page%20showing%20both%20filters.jpg.webp?alt=media&token=a31544df-e5b5-4b8a-aeef-fb2d970ff825"/></td></tr>
<tr><td> <em>Caption:</em> <p>2 filters applied where the items are sorted from high to low in<br>terms of price with heroku URL <br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 3: </em> Add a screenshot of the filter/sort logic from the code</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fmh82%2F2024-08-02T21.09.41filter%20logic%20from%20code.jpg.webp?alt=media&token=8b9ee347-2f72-4fb5-b876-7dd63eb43efa"/></td></tr>
<tr><td> <em>Caption:</em> <p>Code of logic with ucid and data shown at the top<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 4: </em> Briefly explain how the results are shown and how the filters are applied</td></tr>
<tr><td> <em>Response:</em> <p>Inputs were added to the form in order to apply the filters which<br>was used by the user input. The input values in the POST request<br>are then set after the user clicks on the apply filter button. Usually<br>the parameters are empty where the SQL query is adjusted so they are<br>not included when the data is retrieved. If the parameters are set to<br>something, they are binded to the SQL statement. The category filters is set<br>after the items matched the category via name_filter where a partial match is<br>done including the items. A price filter is also used where it is<br>set from high to low as well as having 10 items shown since<br>the results are limited from 10 items on the original webpage.&nbsp;<br></p><br></td></tr>
<tr><td> <em>Sub-Task 5: </em> Add related pull request link(s)</td></tr>
<tr><td> <a rel="noreferrer noopener" target="_blank" href="https://github.com/ItsMeek23/mh82-IT202-451/pull/16#issuecomment-2266270869">https://github.com/ItsMeek23/mh82-IT202-451/pull/16#issuecomment-2266270869</a> </td></tr>
<tr><td> <em>Sub-Task 6: </em> Add a direct link to heroku prod for this file</td></tr>
<tr><td> <a rel="noreferrer noopener" target="_blank" href="https://mh82-prod.herokuapp.com/project//shop.php">https://mh82-prod.herokuapp.com/project//shop.php</a> </td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 3: </em> Show Admin/Shop Owner Product List (this is not the Shop page and should show visibility status) </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="https://user-images.githubusercontent.com/54863474/211707773-e6aef7cb-d5b2-4053-bbb1-b09fc609041e.png"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Screenshot of the Admin List page/results</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fmh82%2F2024-08-03T01.16.12admin%20list%20page.jpg.webp?alt=media&token=f0009545-50f1-4199-a5c2-063243d0ecd2"/></td></tr>
<tr><td> <em>Caption:</em> <p>List products page with heroku URL<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Briefly explain how the results are shown</td></tr>
<tr><td> <em>Response:</em> <p>For the admin pages, a list_products.php file was created where it checks if<br>the user is an admin or shop owner where it uses the has_role{}<br>function. The user will then enter a name to filter the results after<br>the authentication is enabled where the results will be left blank in order<br>to get a list of all the products, The user will then send<br>a POST request where querty statements are made.&nbsp;<div><br></div><div><b>$stmt = $db-&gt;prepare(&quot;SELECT id, name, description,<br>category, stock, created, modified, unit_price, visibility from $TABLE_NAME WHERE name like :name LIMIT<br>10&quot;);</b></div><div><b><br></b></div><div>A placeholder will be inserted where the SQL will be matching incoming statements<br>and the data is retrieved from the html table&nbsp;</div><br></p><br></td></tr>
<tr><td> <em>Sub-Task 3: </em> Add related pull request link(s)</td></tr>
<tr><td> <a rel="noreferrer noopener" target="_blank" href="https://github.com/ItsMeek23/mh82-IT202-451/pull/16#issuecomment-2266304710">https://github.com/ItsMeek23/mh82-IT202-451/pull/16#issuecomment-2266304710</a> </td></tr>
<tr><td> <em>Sub-Task 4: </em> Add a direct link to heroku prod for this file</td></tr>
<tr><td> <a rel="noreferrer noopener" target="_blank" href="https://mh82-prod.herokuapp.com/project//admin/list_products.php">https://mh82-prod.herokuapp.com/project//admin/list_products.php</a> </td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 4: </em> Admin/Shop Owner Edit button </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="https://user-images.githubusercontent.com/54863474/211707773-e6aef7cb-d5b2-4053-bbb1-b09fc609041e.png"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Add a screenshot showing the edit button visible to the Admin on the Shop page</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fmh82%2F2024-08-03T01.16.38admin%20edit%20button.jpg.webp?alt=media&token=c20ec413-fb39-4bff-a681-5b3b02b60365"/></td></tr>
<tr><td> <em>Caption:</em> <p>Edit button from the shop for admin user with heroku URL<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Add a screenshot showing the edit button visible to the Admin on the Product Details Page</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fmh82%2F2024-08-03T02.01.36admin%20products%20details%20page.jpg.webp?alt=media&token=a2c67766-5feb-4918-b6c4-2eeba62303c7"/></td></tr>
<tr><td> <em>Caption:</em> <p>Edit button for admin user on the product_detail page with heroku URL<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 3: </em> Add a screenshot showing the edit button visible to the Admin on the Admin Product List Page (The admin page)</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fmh82%2F2024-08-03T02.02.56admin%20product%20list%20page.jpg.webp?alt=media&token=bf5c9e06-228c-4625-bee3-27a924035b2c"/></td></tr>
<tr><td> <em>Caption:</em> <p>Edit button for admin user on the list_products page with heroku URL<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 4: </em> Add a before and after screenshot of Editing a Product via the Admin Edit Product Page</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fmh82%2F2024-08-03T02.04.04admin%20edit%20product%20page.jpg.webp?alt=media&token=3719357c-ca13-473a-85e1-5a8f2b1726e2"/></td></tr>
<tr><td> <em>Caption:</em> <p>admin changing the visibility to true for item with a pop message that<br>it was updated successfully<br></p>
</td></tr>
<tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fmh82%2F2024-08-03T02.05.04database%20before%20update.jpg.webp?alt=media&token=1a179e32-4475-4708-a2e1-153e221fb0de"/></td></tr>
<tr><td> <em>Caption:</em> <p>database before update<br></p>
</td></tr>
<tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fmh82%2F2024-08-03T02.05.10database%20after%20update.jpg.webp?alt=media&token=0b859d37-3065-44ef-8578-f724022d52b8"/></td></tr>
<tr><td> <em>Caption:</em> <p>database after update<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 5: </em> Briefly explain the code process/flow</td></tr>
<tr><td> <em>Response:</em> <p>The edit_item php is in the admin pages folder which is the only<br>admin that can edit items where to make sure they have the correct<br>permission, there it a has_role{} to check. The id, created, and modified columns<br>are ignored as they aren&#39;t changed by the user input. After the information<br>is submitted, the update_products{} function is called where it takes the table name,<br>id, and post request as parameters which is used for the UPDATE statement.&nbsp;<br></p><br></td></tr>
<tr><td> <em>Sub-Task 6: </em> Add related pull request link(s)</td></tr>
<tr><td> <a rel="noreferrer noopener" target="_blank" href="https://github.com/ItsMeek23/mh82-IT202-451/pull/16#issuecomment-2266331933">https://github.com/ItsMeek23/mh82-IT202-451/pull/16#issuecomment-2266331933</a> </td></tr>
<tr><td> <em>Sub-Task 7: </em> Add a direct link to heroku prod for this file</td></tr>
<tr><td> <a rel="noreferrer noopener" target="_blank" href="https://mh82-prod.herokuapp.com/project//admin/edit_products.php?id=1">https://mh82-prod.herokuapp.com/project//admin/edit_products.php?id=1</a> </td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 5: </em> Product Details Page </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="https://user-images.githubusercontent.com/54863474/211707773-e6aef7cb-d5b2-4053-bbb1-b09fc609041e.png"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Add a screenshot showing the button (clickable item) that directs the user to the Product Details Page</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fmh82%2F2024-08-03T02.20.00clickable%20over%20product%20details%20page.jpg.webp?alt=media&token=ea8d88bc-bc11-45b8-818a-a18a0cdce98f"/></td></tr>
<tr><td> <em>Caption:</em> <p>The section is able to be clicked by the user which indicated by<br>the yellow hovering clicker with heroku URL<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Add a screenshot showing the result of the Product Details Page</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fmh82%2F2024-08-03T02.20.55result%20of%20products%20details%20page.jpg.webp?alt=media&token=9a9361f9-d9d1-4e92-b55c-1eac4c384f71"/></td></tr>
<tr><td> <em>Caption:</em> <p>Products details page with heroku IRL after being clicked<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 3: </em> Briefly explain the code process/flow</td></tr>
<tr><td> <em>Response:</em> <p>An anchor tag was created in the product card with a stretchable link<br>class where it made the entire card clickable with the pointer. After whatever<br>section is clicked on the prodcut_details.php page, the php was set to the<br>id of the item. The product_details page takes account of stock items that<br>are not available on the webpage and will not show them on the<br>homepage. The product_details will use a GET request from the id which will<br>be generated creating a SQL statement. Once the statement is successful, the container<br>will be displayed with all the information about the certain item requested and<br>if it isn&#39;t successful, the user will be directed to the original homepage.&nbsp;<br></p><br></td></tr>
<tr><td> <em>Sub-Task 4: </em> Add related pull request link(s)</td></tr>
<tr><td> <a rel="noreferrer noopener" target="_blank" href="https://github.com/ItsMeek23/mh82-IT202-451/pull/16#issuecomment-2266340022">https://github.com/ItsMeek23/mh82-IT202-451/pull/16#issuecomment-2266340022</a> </td></tr>
<tr><td> <em>Sub-Task 5: </em> Add a direct link to heroku prod for this file (can be any specific item)</td></tr>
<tr><td> <a rel="noreferrer noopener" target="_blank" href="https://mh82-prod.herokuapp.com/project//product_details.php?id=4">https://mh82-prod.herokuapp.com/project//product_details.php?id=4</a> </td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 6: </em> Add to Cart </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="https://user-images.githubusercontent.com/54863474/211707773-e6aef7cb-d5b2-4053-bbb1-b09fc609041e.png"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Add a screenshot of the success message of adding to cart</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fmh82%2F2024-08-03T03.15.49adding%20to%20cart.jpg.webp?alt=media&token=42703a07-acc7-4bc9-aa91-e4420e4ebf4b"/></td></tr>
<tr><td> <em>Caption:</em> <p>Item added to cart success message with heroku URL<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Add a screenshot of the error message of adding to cart (i.e., when not logged in)</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fmh82%2F2024-08-03T03.16.16error%20message%20of%20adding%20to%20cart.jpg.webp?alt=media&token=f160574c-9d1a-4ecb-9e9a-ef468bdc40f7"/></td></tr>
<tr><td> <em>Caption:</em> <p>Error pop up message for non logged in user which will redirect user<br>to login page with url visible<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 3: </em> Add a screenshot of the Cart table with data in it</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fmh82%2F2024-08-03T03.17.08cart%20table%20with%20data%20in%20it.jpg.webp?alt=media&token=8b174f1e-2270-482d-9a16-f4f127e8258a"/></td></tr>
<tr><td> <em>Caption:</em> <p>Database of the cart with the item added highlighted<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 4: </em> Tell how your cart works (1 cart per user; multiple carts per user)</td></tr>
<tr><td> <em>Response:</em> <p>One cart is designated per user where the user can have only 1<br>cart product_id and user_id designated to them with a unique key&nbsp;<br></p><br></td></tr>
<tr><td> <em>Sub-Task 5: </em> Explain the process of add to cart</td></tr>
<tr><td> <em>Response:</em> <p>The cart checks if the user is first logged in and after the<br>user clicked on add to cart, the user is directed to the cart.php<br>page with add and the item_id in the request. In the cart.php file,<br>a switch statement that runs on action through a POST request. The product<br>id is binded for the add where a complete SQL statement run.&nbsp;<div><br></div><div>$query =<br>&quot;INSERT INTO Cart (product_id, desired_quantity, unit_price, user_id) VALUES (:pid, :dq, (SELECT unit_price from<br>PRODUCTS WHERE id = :pid), :uid) ON DUPLICATE KEY UPDATE desired_quantity = desired_quantity<br>+ :dq&quot;; Once an item is added to the cart, a message is<br>displayed. If a failure occurs, an error message will be displayed where it<br>will be logged.&nbsp;</div><br></p><br></td></tr>
<tr><td> <em>Sub-Task 6: </em> Add related pull request link(s)</td></tr>
<tr><td> <a rel="noreferrer noopener" target="_blank" href="https://github.com/ItsMeek23/mh82-IT202-451/pull/16#issuecomment-2266359875">https://github.com/ItsMeek23/mh82-IT202-451/pull/16#issuecomment-2266359875</a> </td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 7: </em> User will be able to see their Cart </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="https://user-images.githubusercontent.com/54863474/211707773-e6aef7cb-d5b2-4053-bbb1-b09fc609041e.png"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Add screenshot of the Cart View</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fmh82%2F2024-08-03T23.21.10cart%20view.jpg.webp?alt=media&token=c8efd1ad-75ff-44f0-86c3-cddbb02119c6"/></td></tr>
<tr><td> <em>Caption:</em> <p>Cart with subtotal of items where the total is added up correctly. Each<br>item name is able to be clicked to the products details page with<br>heroku URL<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Explain how the cart is being shown from a code perspective along with the subtotal and total calculations</td></tr>
<tr><td> <em>Response:</em> <p>A SQL query statement is ran on the Cart table after the add<br>and edit logic is cleared so the cart is always updated with the<br>latest information stored in it. Cart data is retrieved from the database where<br>a SQL query is used to display items in a table. This table<br>displays columns for the item, cost, quantity and subtotal price. The HTML content<br>is generated by PHP where it finds the total cost of the items<br>that were stored in the cart where it can give options to the<br>users such as deleted items, checking the quantity, and clearing the cart altogether.<br>A message will be displayed if there are no items present in the<br>cart.&nbsp;<div><br></div><div>The SQL query statement is used =&nbsp;</div><div>&nbsp;</div><div>$query = &quot;SELECT cart.id, product.name, product.stock, cart.unit_price,<br>(cart.unit_price * cart.desried_quantity) as subtotal, cart.desired_quantity FROM products as product JOIN Cart as<br>cart on cart.product_od = product.id WHERE cart.user_id = :uid&quot;;</div><br></p><br></td></tr>
<tr><td> <em>Sub-Task 3: </em> Add related pull request link(s)</td></tr>
<tr><td> <a rel="noreferrer noopener" target="_blank" href="https://github.com/ItsMeek23/mh82-IT202-451/pull/16#issuecomment-2267189475">https://github.com/ItsMeek23/mh82-IT202-451/pull/16#issuecomment-2267189475</a> </td></tr>
<tr><td> <em>Sub-Task 4: </em> Add a direct link to heroku prod for this file</td></tr>
<tr><td> <a rel="noreferrer noopener" target="_blank" href="https://mh82-prod.herokuapp.com/project//cart.php">https://mh82-prod.herokuapp.com/project//cart.php</a> </td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 8: </em> User can update cart quantity </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="https://user-images.githubusercontent.com/54863474/211707773-e6aef7cb-d5b2-4053-bbb1-b09fc609041e.png"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Show a before and after screenshot of Cart Quantity update</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fmh82%2F2024-08-03T23.58.39before%20updating%20quantity%20highlighted.jpg.webp?alt=media&token=634cabb4-9295-41f0-b5b1-c4fe71f82b2b"/></td></tr>
<tr><td> <em>Caption:</em> <p>Cart before updating quantity highlighted with heroku URL<br></p>
</td></tr>
<tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fmh82%2F2024-08-03T23.59.22after%20updated%20quantity%20highlighted.jpg.webp?alt=media&token=1b276c22-c372-43ab-aa7b-ce6fef2cbb3f"/></td></tr>
<tr><td> <em>Caption:</em> <p>Cart after updating quantity highlighted with heroku URL<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Show a before and after screenshot of setting Cart Quantity to 0</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fmh82%2F2024-08-04T00.00.02before%20updated%20quantity%20to%200.jpg.webp?alt=media&token=d2a74430-ed1d-4993-8d96-2e8c58369fa0"/></td></tr>
<tr><td> <em>Caption:</em> <p>Cart before updating quantity to 0 with heroku URL<br></p>
</td></tr>
<tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fmh82%2F2024-08-04T00.08.01after%20updating%20quantity%20to%200.jpg.webp?alt=media&token=1605fae8-a29a-4731-bc5d-487e5258e934"/></td></tr>
<tr><td> <em>Caption:</em> <p>Cart after updating quantity to 0 with heroku URL<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 3: </em> Show how a negative quantity is handled</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fmh82%2F2024-08-04T00.08.41negative%20quantity%20is%20handled.jpg.webp?alt=media&token=f3802ca3-1960-4a30-af54-1efdd31c6593"/></td></tr>
<tr><td> <em>Caption:</em> <p>Error message is displayed after the user tried to enter a negative value<br>with heroku URL<br></p>
</td></tr>
<tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fmh82%2F2024-08-04T00.13.45error%20message%20with%20negative%20quantity.jpg.webp?alt=media&token=56b9f3e4-265d-4484-8ccc-6566a6897714"/></td></tr>
<tr><td> <em>Caption:</em> <p>Error message is displayed after the user tried to enter a negative value<br>which is shown after the min restriction was removed with heroku URL<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 4: </em> Explain the update process including how a value of 0 and negatives are handled</td></tr>
<tr><td> <em>Response:</em> <p>A message will be displayed if the quantity is set to less than<br>0 for a specific item&nbsp; with a warning that the quantity can&#39;t be<br>set to a negative number. The function die() is called to stop the<br>execution of the script and the user will be sent to the cart<br>page if this is done.&nbsp; A message will be displayed if the quantity<br>for an item is set to 0 where the code will delete the<br>item by using a DELETE query in the database indicating that the item<br>has been removed from the cart.&nbsp;<br></p><br></td></tr>
<tr><td> <em>Sub-Task 5: </em> Add related pull request link(s)</td></tr>
<tr><td> <a rel="noreferrer noopener" target="_blank" href="https://github.com/ItsMeek23/mh82-IT202-451/pull/16#issuecomment-2267212932">https://github.com/ItsMeek23/mh82-IT202-451/pull/16#issuecomment-2267212932</a> </td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 9: </em> Cart Item Removal </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="https://user-images.githubusercontent.com/54863474/211707773-e6aef7cb-d5b2-4053-bbb1-b09fc609041e.png"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Add a before and after screenshot of deleting a single item from the Cart</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fmh82%2F2024-08-04T05.04.05before%20removing%201st%20item.jpg.webp?alt=media&token=f39e779f-4334-4ff8-af4c-c9049e81c773"/></td></tr>
<tr><td> <em>Caption:</em> <p>Cart before removing 1st item in cart with heroku URL<br></p>
</td></tr>
<tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fmh82%2F2024-08-04T05.04.14after%20removing%201st%20item.jpg.webp?alt=media&token=55c4e2aa-be9b-45b1-833a-12d70d59cdb2"/></td></tr>
<tr><td> <em>Caption:</em> <p>Cart after removing 1st item in cart with heroku URL<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Add a before and after screenshot of clearing the cart</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fmh82%2F2024-08-04T05.05.18before%20clearing%20it%20out.jpg.webp?alt=media&token=04f4929e-7431-449d-9440-acfb4f484b89"/></td></tr>
<tr><td> <em>Caption:</em> <p>Cart before clearing it out with heroku URL<br></p>
</td></tr>
<tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fmh82%2F2024-08-04T05.05.24after%20clearing%20it%20out.jpg.webp?alt=media&token=feef486d-f65d-48ea-8539-f6014ad546af"/></td></tr>
<tr><td> <em>Caption:</em> <p>Cart after clearing it out with heroku URL<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 3: </em> Briefly explain how each delete process works</td></tr>
<tr><td> <em>Response:</em> <ol><br><li>Delete Case: Code is designed to remove a specific item that was<br>selected from the cart. The deleted item is identified by cart_id which is<br>found from the $_POST data. SQL query statement DELETE FROM CARTWHERE id =<br>:cid AND user_id = :uid the &quot;cart_id&quot; and &quot;user_id&quot; are placeholder values to<br>prevent SQL injection. The true values are binded to the placeholders using the<br>bindValue() method. The SQL query is executed using the execute() method where if<br>it is executed correctly, a message will be displayed stating that the item<br>has been removed from the cart. An error message will be displayed if<br>there is an exception during the query where it will indicate there was<br>an error.<div><br></div><div>2. Clear Case: Code is designed to remove all selected items in<br>the cart for the user. SQL query statement DELETE FROM CartWHERE user_id =<br>:uid is used as a placeholder where the the value of the user_id<br>is binded to the placeholder using the bindValue()metho. The SQL query is executed<br>using the execute() method where if it is executed correctly, a message will<br>be displayed stating that the item has been removed from the cart. An<br>error message will be displayed if there is an exception during the query<br>where it will indicate there was an error.</div><br></li><br></ol><br></td></tr>
<tr><td> <em>Sub-Task 4: </em> Add related pull request link(s)</td></tr>
<tr><td> <a rel="noreferrer noopener" target="_blank" href="https://github.com/ItsMeek23/mh82-IT202-451/pull/16#issuecomment-2267357921">https://github.com/ItsMeek23/mh82-IT202-451/pull/16#issuecomment-2267357921</a> </td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 10: </em> Misc </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="https://user-images.githubusercontent.com/54863474/211707773-e6aef7cb-d5b2-4053-bbb1-b09fc609041e.png"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Add screenshots showing which issues are done/closed (project board) Incomplete Issues should not be closed (Milestone2 issues)</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fmh82%2F2024-08-04T06.16.29project%20board%201.png.webp?alt=media&token=8615cbad-5d47-46e1-be82-3a2c24076408"/></td></tr>
<tr><td> <em>Caption:</em> <p>Project board for all Milestone 2 issues closed in the Milestone 2 DONE<br>column where all objectives were complete so no issues were had<br></p>
</td></tr>
<tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fmh82%2F2024-08-04T06.16.31project%20board%202.png.webp?alt=media&token=31ba915d-09f1-4776-b9c0-59c2f5613d90"/></td></tr>
<tr><td> <em>Caption:</em> <p>Project board for all Milestone 2 issues closed in the Milestone 2 DONE<br>column where all objectives were complete so no issues were had<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Add a link to your herok prod project's login page</td></tr>
<tr><td> <a rel="noreferrer noopener" target="_blank" href="https://mh82-prod.herokuapp.com/project/">https://mh82-prod.herokuapp.com/project/</a> </td></tr>
</table></td></tr>
<table><tr><td><em>Grading Link: </em><a rel="noreferrer noopener" href="https://learn.ethereallab.app/homework/IT202-AR451-M2024/it202-milestone-2-shop-project/grade/mh82" target="_blank">Grading</a></td></tr></table>
