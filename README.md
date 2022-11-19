## CBWA - CA2
Docker Image using Alpine, Node.js and Nginx.

## Usage
1. Download the dockerfile
2. Execute Docker Desktop
3. If the image is hosted in your machine you should access the directory where the dockerfile is.
``` cd /Desktop/ImageDirectory ```
4. Inside the directory build the image
``` docker build -t static-website . ```
5. Run the image
``` docker run -it --rm -p 8080:8080 static-website ```
6. And finally you can access in the browser
``` http://localhost:8080 ```

## References
