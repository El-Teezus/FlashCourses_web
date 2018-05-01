# **REST API Calls Made Easy**

Use Postman and VSCode REST Client for intuitive API Calls.

## **Using Postman**

### **What is Postman?**

	Postman is a Web Application which does API requests to access an API endpoint! 

### **What’s an API Call?**

	An API call is an access point involved with an HTTP method. 

	Mostly, we will be using GET, POST, PUT DELETE. 

		GET: grab data.
		POST: add data to an existing file.
		PUT: replace file or resource
		DELETE: delete data.

### **How do I Download Postman?**

	Go to [https://www.getpostman.com/apps](https://www.getpostman.com/apps) and download the right version.

### **How Do I Install Postman?**

**macOS:** drag the file into the Applications folder. Double click postman

**Windows:** Download the setup file and run the installer.

**Linux:**

	* wget https://dl.pstmn.io/download/latest/linux64 -O postman.tar.gz 

	* sudo tar -xzf postman.tar.gz -C /opt 

	* rm postman.tar.gz sudo ln -s /opt/Postman/Postman /usr/bin/postman



### **How do I use Postman?**

	Postman is very intuitive.

	Enter postman-echo.com/get into the URL field, click send.

	You’ll get a JSON response, or error message back.



### **Why Should I Use Postman?**

	* History makes it easy to search for tests you’ve done

	* CLI integration

	* Create and save requests and access them later.

### **Why Shouldn’t I Use Postman?**

	* Tab view can be somewhat messy.

### **For More information:**

	* https://medium.com/aubergine-solutions/api-testing-using-postman-323670c89f6d

## **Using VSCode REST Client**

### **What is VSCode REST Client?**

	* VSCode REST Client is an extension that allows the user to do API Calls inside VSCode.

	* Powerful combined with having a Terminal, Debugger, and Git functionality inside the editor. 

	* Means you don’t have to leave the editor for different things, eliminating decision fatigue.

### **Wait…. What’s VSCode?**

	* VSCode is Visual Studio Code, which is Microsoft’s Text Editor.

	* It’s different from Visual Studio.

    		* On multiple platforms rather than just Windows/MAC

    		* Does not have the UI of Visual Studio.

    		* Isn’t inherently made for .NET projects.

### **How do I Install VSCode REST Client?**

	* If you don’t have it, Install VSCode:

    	* Download the .deb package from [here.](https://code.visualstudio.com/download) [https://code.visualstudio.com/download](https://code.visualstudio.com/download)

    	* IF USING THE GRAPHIC SOFTWARE CENTER: double click!

    	* IF USING THE CLI, follow the [installation process](https://code.visualstudio.com/docs/setup/linux), reposted below:

        	* Taken from https://code.visualstudio.com/docs/setup/linux

        	* *(In the path ) *sudo dpkg -i *<file>*.deb

        	* sudo apt-get install -f *# Install dependencies*

	* Once VSCode is up and running:

    		* Use Quick Open (Ctrl + P) 

    	* Copy and paste the following into the search bar:

        	* ext install humao.rest-client

        * Press enter

### **How do I do API Calls?**

	* Create a file with a .http extension and access it through VSCode.

	* In your file, use the following syntax

<##### delimiter>
               REQUEST TYPE ENDPOINT
<##### delimiter>


	* Press Ctrl + Alt + R, or click send request (which appears when the formatting is correct ) 

	* A new window will open up with the results of the request.

### **Wait…. Could I see some examples?**
	
	GET https://example.com/comments/1 HTTP/1.1

	###

	GET https://example.com/topics/1 HTTP/1.1

	###

	POST https://example.com/comments HTTP/1.1
	content-type: application/json

	{
    		"name": "sample",
    		"time": "Wed, 21 Oct 2015 18:27:50 GMT"
	}


### **Why Should I Use REST Client?** 

	* Can create REST calls without switching programs.

	* Function calls are easier to access and laid out in text editor.

### **Why Shouldn’t I Use REST Client?**

	* It requires the user to use VSCode as a text editor.

	* Higher learning curve than Postman

### **Where Can I Learn More About REST Client?**

	* For more indepth use of REST Client, refer to [the marketplace](https://marketplace.visualstudio.com/items?itemName=humao.rest-client)

    		* [https://marketplace.visualstudio.com/items?itemName=humao.rest-client](https://marketplace.visualstudio.com/items?itemName=humao.rest-client)

	* Can also refer to the [README](https://github.com/Huachao/vscode-restclient/blob/master/README.md):

	    * https://github.com/Huachao/vscode-restclient/blob/master/README.md

