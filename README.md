
# Crack StarUML | 6.2.2 | 6.3.0

This script is designed to remove license restrictions for **StarUML tested in versions 6.2.2 and 6.3.0**, including the removal of watermarks on exports.

## Prerequisites
1.  **Sudo Permissions**: Required if StarUML is installed in `/opt`.
1. **Node.js**  
3. **Bash**

## Initialization
   ```bash
   git clone git@github.com:Nother01/Crack_StarUML.git
   cd Crack_StarUML
   chmod 755 starUML.sh
```   

## Usage
Run the script with or without specifying the path to the StarUML installation folder, 

 1. **Automatic detection of the StarUML path**:    
	 ```
    sudo ./starUML.sh
	```
2.  **With specified path**:
	  ```
    sudo ./starUML.sh /path/to/StarUML
	```
\
**Output**	
```
StarUML directory provided: /opt/StarUML

[1] Navigated to /opt/StarUML/resources
[2] Checking if asar is already installed...
[3] Extracting app.asar...
[4] Checking StarUML version. Tested versions for this patch: 6.2.2 6.3.0
        -> Version found in package.json: 6.3.0
[5] Copying files from /home/StarUMLCrack/patch to /opt/StarUML/resources/app/src/engine...
[6] Packing app.asar...

StarUML successfully patched!
```
After the script successfully applied, simply restart the StarUML executable to use the patched version.
## Credit
Code inspired by this [post](https://gist.github.com/trandaison/40b1d83618ae8e3d2da59df8c395093a?permalink_comment_id=5079514)

