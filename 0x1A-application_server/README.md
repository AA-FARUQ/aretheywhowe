# AirBnB Clone V2 - Web Framework

## Description

This project is part of the AirBnB clone series. The objective is to set up a development environment to serve the web framework content using Flask on the web-01 server.

## Requirements

- Complete task #3 of your SSH project for web-01.
- Install the net-tools package: `sudo apt install -y net-tools`.
- Git clone your AirBnB_clone_v2 on your web-01 server.
- Configure the file `web_flask/0-hello_route.py` to serve its content from the route `/airbnb-onepage/` on port 5000.
- The Flask application object must be named `app`.

## Usage

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/AirBnB_clone_v2.git
    cd AirBnB_clone_v2
    ```

2. **Run the Flask application**:
    ```bash
    python3 -m web_flask.0-hello_route
    ```

3. **Access the application**:
    Open your browser and go to `http://<your-server-ip>:5000/airbnb-onepage/` or use `curl`:
    ```bash
    curl 127.0.0.1:5000/airbnb-onepage/
    ```

## Example

### Window 1:
```bash
ubuntu@229-web-01:~/AirBnB_clone_v2$ python3 -m web_flask.0-hello_route
 * Serving Flask app "0-hello_route" (lazy loading)
 * Environment: production
   WARNING: Do not use the development server in a production environment.
   Use a production WSGI server instead.
 * Debug mode: off
 * Running on http://0.0.0.0:5000/ (Press CTRL+C to quit)

ubuntu@229-web-01:~/AirBnB_clone_v2$ curl 127.0.0.1:5000/airbnb-onepage/
Hello HBNB!


This README.md file contains all the necessary instructions and information for setting up the development environment, running the Flask application, and accessing it. Make sure to replace `yourusername` with your actual GitHub username.
