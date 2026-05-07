# Sentimax

## TODO List
■ Nick TODO
• try to fix image text scraping off images w/ no text
• figure out how to combine scikitlearn, tensorflow, and hugging face together  
    →bring in LLAMA3, BERT  
• look at f1-score and if score value is low, consider providing more examples to get that number up  
    - the higher the f1-score, the better  
• use the following code to check the f1-score and such  
    ```  
    y_pred = ensemble_model.predict(X_test)  
    print(classification_report(y_test, y_pred))  
    ```  
• make the frontend responsive
    →tailwind, framer motion, react responsive, react intersection observer, radix ui, chakra ui
    →if you want full UI control, go with Tailwind CSS.
    →if you need responsive animations, use Framer Motion
    →if you want JS-based media queries, try React Responsive
    →if you need lazy loading, use React Intersection Observer

## How to Use
1) Make sure the current directory is `Sentimax-Deep-Learning-V1`
2) Enter the virtual environment: `.\venv\Scripts\activate`
3) Install the required libraries: `pip install -r requirements.txt`
4) Run the Flask backend: `python flask_backend.py`
5) Open a new terminal
6) Navigate to the frontend folder: `cd react-vite-app`
7) Run the frontend: `npm run dev`
8) Open the localhost link that appears in the terminal
9) To stop the project:
   - Press `Ctrl + C` in both terminals
   - Type `deactivate` to exit the virtual environment