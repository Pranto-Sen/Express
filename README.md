# Express

1. First run this commad ```$ npm init```
2. Install express.js ```$ npm install express```
3. Create a file index.js and past this code
    ``` const express = require('express')
    const app = express()
    const port = 3000
    
    app.get('/', (req, res) => {
      res.send('Hello World!')
    })
    
    app.listen(port, () => {
      console.log(`Example app listening on port ${port}`)
    })
    ```
4. Run the app with the following command:
    ```
    $ node app.js
    ```
5. Now go to a browser and paste this url
    ```
    https://localhost/3000
    ```
6. Nodemon is a tool that helps develop Node.js based applications by automatically restarting the node application when file changes in the directory are detected. This is very useful in development environments to speed up the development process.
   ```
   npm install -g nodemon
   instead of running node index.js, use nodemon index.js
   ```

![Screenshot from 2024-07-16 12-40-18](https://github.com/user-attachments/assets/122aa812-7612-4680-9e3a-1a49e1eb74d2)
