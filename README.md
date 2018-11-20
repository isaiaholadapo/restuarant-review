
## Basic functionality

Main page:
  - Map - showing the restaurants addresses
  - 2 dropdown filters - to filter the restaurants according to: "Neighborhood", and "Cuisine".
  - Restaurant cards - showing photo, name, neighborhood, address, view details button

Individual restaurant page:
  - Previous mentioned details (photo, name, neighborhood, address)
  - Individual restaurant map
  - Opening hours
  - Reviews for the restaurant

### Accessiblity:
  - Accessible images with alternate text
  - Focus management allows easy navigation of the site
  - Semnatically defined elements and ARIA roles

### Offline Availability:
  Service worker enables the app to be available offline after the first use.


## Local usage

  1. After download, use a simple HTTP server to serve up the site files on your local computer.
  - If you don't have Python installed, navigate to Python's [website](https://www.python.org/) to download and install the software.
  - Navigate to project folder in your terminal.
  - Check the version of Python you have: `python -V`.
  - If you have Python 2.x, spin up the server with `python -m SimpleHTTPServer 8000` (or some other port, if port 8000 is already in use.)
  - For Python 3.x, you can use `python3 -m http.server 8000`

  2. With your server running, visit the site: `http://localhost:8000`.
