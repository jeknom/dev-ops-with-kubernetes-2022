The client needs to be built with the `VITE_SERVER_URL` build arg that points to the server. Otherwise, you will run into CORS errors. So if you want to test this in your own cluster, you will need to build your own image with the server IP/URL provisioned by your cloud provider.