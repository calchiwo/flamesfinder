# flamesfinder
# FlamesFinder

FlamesFinder is a simple FLAMES compatibility web app. You enter two names. The app calculates the FLAMES result and shows a clear label with an image. Everything in this project was coded on a phone.

## Features

- Clean mobile friendly UI  
- Name inputs for both users  
- FLAMES logic handled in Python through Pyodide  
- Instant results with images  
- Clear reset button for quick tests  

## How It Works

The Python logic runs inside the browser with Pyodide. The app sends both names to the Python function. The function returns a label and an image key. The UI displays the final result.

## Project Structure

- `index.html` contains the full interface  
- `flames.py` holds the FLAMES logic  
- `images/` contains all result images  
- Everything runs in the browser  
- No backend needed  

## Run Locally

1. Clone the repo.

```
git clone https://github.com/calchiwo/flamesfinder
```

2. Open `index.html` in your browser.  
3. Add the `flames.py` file and `images` folder in the same directory.

## Deployment

The project is deployed at:

**https://flamesfinder.vercel.app**

## Credits

Built by **Calchiwo**.  
This is a fun tool. Use it lightly.
