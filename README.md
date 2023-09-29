
## Image URL Collection Steps

To retrieve image URLs from a website, follow these steps:

1. **Inspect the Webpage:**
   Open the webpage from which you want to collect image URLs. Right-click on the page and select "Inspect" to open the developer tools.

2. **Navigate to the Network Tab:**
   In the developer tools, go to the "Network" tab. Ensure the "img" file type is selected to filter for image files.

3. **Refresh the Webpage:**
   Refresh the webpage using Ctrl + R to load the images.

4. **Copy as HAR:**
   Right-click on any image file in the network tab, select "Copy," and then choose "Copy all as HAR."

5. **Access the Console:**
   Navigate to the console in the developer tools.

6. **Process the HAR Data:**
   Type the following command in the console:
   ```javascript
   var har = /* Paste the copied HAR data here */;
   ```

7. **Execute the Code:**
   Press Enter after typing the command.

8. **Extract Image URLs:**
   Copy and Paste the code given in the webimages.js file in the console. Press Enter.

9. **Collect Image URLs:**
   Press Enter after typing the command to display and collect all image URLs.

You can then use these gathered image URLs for your intended purposes.

---