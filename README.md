
## 📁 Setup and Structure

### Step: Package Management
- Write the setup for importing local packages in `setup.py` and `pyproject.toml` files.
- **Tip**: Learn more about these files from `crashcourse.txt`.

### Step: Virtual Environment and Dependencies
- Create a virtual environment and install required dependencies from `requirements.txt`:
  ```bash
  conda create -n vehicle python=3.10 -y
  conda activate vehicle
  pip install -r requirements.txt
  ```
- Verify the local packages by running:
  ```bash
  pip list
  ```


## 📊 MongoDB Setup and Data Management

### Step 4: MongoDB Atlas Configuration
1. Sign up for [MongoDB Atlas](https://www.mongodb.com/cloud/atlas) and create a new project.
2. Set up a free M0 cluster, configure the username and password, and allow access from any IP address (`0.0.0.0/0`).
3. Retrieve the MongoDB connection string for Python and save it (replace `<password>` with your password).

### Step 5: Pushing Data to MongoDB
1. Create a folder named `notbeook' and take data set
2. create `mongoDB_start` and create a notebook file `mongoDB_demo.ipynb` and test these two.
3. Use the notebook to push data to the MongoDB database.
4. Verify the data in MongoDB Atlas under Database > Browse Collections.
