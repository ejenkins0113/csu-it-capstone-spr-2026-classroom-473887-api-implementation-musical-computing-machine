[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/zN2AskmG)
# XKCD Comic Viewer

[Add your 2-3 sentence description of what your application does here]

## Features Implemented

Check off the features you implemented (must have at least 4 and 2 are implemeted for you already):

- [X] Feature #1: Display the Latest Comic
- [X] Feature #2: Display a Specific Comic by Number
- [x] Feature #3: Random Comic Button
- [ ] Feature #4: Navigation (Previous/Next)
- [x] Feature #5: Search by Comic Number Form
- [ ] Feature #6: Display Multiple Recent Comics

## Technologies Used

- Python 3.8+
- Flask 3.0.0
- Requests 2.31.0
- XKCD API

## Installation and Setup

### Prerequisites
- Python 3.8 or higher installed
- pip (Python package manager)

### Steps to Run

1. Clone or download this repository

2. Navigate to the project directory in your terminal:
   ```
   cd projectName
   ```

3. Install dependencies:
   ```
   pip install -r requirements.txt
   ```

4. Run the application:
   ```
   python app.py
   ```

5. Open your web browser and go to:
   ```
   http://localhost:5000
   ```

## Usage

When users open the website, the latest XKCD comic is displayed automatically. 
They can click the Random Comic button to see a random comic at any time. 
If they know a specific comic number, they can use the search feature to enter that number and load it directly.

The app makes it easy to move between comics using the navigation buttons when available. 
Overall, users can browse, search, and explore different comics in a simple and interactive way.

## Screenshots

[Add screenshots of your application here - you can drag and drop images into GitHub or use Markdown image syntax]

Example:
```
![Latest Comic View](screenshots/latest-comic.png)
![Search Feature](screenshots/search.png)
```

## API Endpoints Used

- `GET /info.0.json` - Fetches the latest comic
- `GET /{comic_number}/info.0.json` - Fetches a specific comic by number

[Write 2-3 paragraphs about:]
- What challenges did you face while working on this assignment?
One of the biggest challenges I faced during this assignment was learning how HTML connects with Flask routes. I struggled with understanding how data from the backend gets passed into the template and displayed on the page. There were several times when my buttons would not show up, even though my code looked correct. I also ran into route errors where Flask said I was overwriting an existing function, which confused me at first.

- How did you solve them?
I solved these issues by carefully reviewing my routes, making sure each function had a unique name, and checking that I was passing the correct variables into render_template(). Debugging taught me to slow down and test one change at a time instead of changing multiple things at once. Over time, I became more comfortable reading error messages and understanding what they meant.

- What did you learn about APIs?
Working with APIs helped me understand how web applications retrieve and display live data. I learned how to send requests, handle JSON responses, and manage errors like invalid comic numbers. This project showed me how frontend and backend development must work together for a web app to function properly.

## Future Improvements

[Optional: What would you add if you had more time?]
I would have added the previous/next funtion, I did try it at first but I was not able to show the button. But I think the issue was that I forgotten to surround the block with <div></div>

## Author

[Elijah Jenkins]