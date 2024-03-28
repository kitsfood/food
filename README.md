# Kitsilano small grocer prices
A thin frontend over a csv file to make it easily filtered and sortable and published to the web via Github Pages. 

## Setup
*If any of these steps are too foreign to you, ask chatgpt to explain how to do it - i.e. https://chatgptdemo.info/chat/*

- Open the template google sheet - [link](https://docs.google.com/spreadsheets/d/1eVaW3fwBo1cY_s-lBoa5PlfhjAqHATqM7t9OSH1GZ-I/edit#gid=0)
  - *You're also free to create your own spreadsheet from scratch.  This template is only for convenience, as it includes a bunch of produce items to choose from and a script to automatically update the 'Last Update' column whenever a change is made to a row.*
- Copy it  

  ![image](https://github.com/kitsfood/food/assets/5546810/5cf078ca-0ace-4c7f-b53f-d7d2f9100ebb)

- Publish it to the web in csv format and copy the link for later

- Create a github repository
- Add a file and name it `index.html`
- Copy and paste the code from [raw.githubusercontent.com/kitsfood/food/main/index.html](https://raw.githubusercontent.com/kitsfood/food/main/index.html) into your `index.html` file
- In your `index.html`, change the `docURL` variable to the link to your google sheet csv file that was published in the earlier step
  
  ![image](https://github.com/kitsfood/food/assets/5546810/93a7a2a3-16b9-48d4-9170-519ca76bef80)  
  
- Commit the changes  
  - The default settings in the resulting prompt should be fine.  
  
  ![image](https://github.com/kitsfood/food/assets/5546810/8bb9c237-e01a-4b07-aa4a-e9d12bfcb066)
  
    
- Enable `Github Pages` for your repository  
  - Click on the `Settings` tab at the top of the repository.
  - Scroll down to the `Pages` section.
  - Under the `Branch` section, select `main`, leave the folder as `/(root)`
  - Click the `Save` button
  - After 5-10 seconds, you should see the URL where the html is published.  If not, try refreshing the page.  
    
    ![image](https://github.com/kitsfood/food/assets/5546810/98fff9c4-b6bd-41b8-9c00-51d45297a2c3)


