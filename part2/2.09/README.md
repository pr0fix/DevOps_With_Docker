# Exercise 2.9

To get the buttons working I removed 5000 and 8080 ports from docker compose frontend and backend configuration since the routes and ports are defined in the nginx.conf file. I also removed the "REACT_APP_BACKEND_URL" from frontend dockerfile and REQUEST_ORIGIN from backend dockerfile since they were no longer needed with the reverse proxy configuration.
