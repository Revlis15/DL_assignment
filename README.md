# NGUYEN TRAN NGHIA - 20225452

### Usage

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/Revlis15/DL_assignment.git
   cd DL_assignment
   ```

2. **Download the Checkpoint**:

   Download the checkpoint from this link:

   [Model Checkpoint](https://drive.google.com/drive/folders/1w544UWTUD5NC8mrzFtN_E5jmm4Z6WlAL?usp=drive_link)

3. **Create a Virtual Environment and Install Requirements**:

   - **On Windows**:

     ```bash
     python -m venv venv
     venv\Scripts\activate
     pip install -r requirements.txt
     ```

   - **On macOS/Linux**:

     ```bash
     python3 -m venv venv
     source venv/bin/activate
     pip install -r requirements.txt
     ```

4. **Run the Inference Script**:

   - **On Windows**:

     ```bash
     python infer.py --image_path image.jpeg
     ```

   - **On macOS/Linux**:

     ```bash
     python3 infer.py --image_path image.jpeg
     ```
