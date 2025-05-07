# STREAMLIT-ACTIVITIES

![f4c2cbd5-81ea-4270-9dbd-389b8fd06e73](https://github.com/user-attachments/assets/6ec6f005-a9dd-40ea-83d6-95ca724deb49)
![40e3dff7-daa2-4ffe-b3cf-1e8b59c7935b](https://github.com/user-attachments/assets/784f868d-5234-4e07-a425-400eed6d27d6)
![f12dbd62-d8e![df1f1c6c-7069-457f-a4be-017009c475ee](https://github.com/user-attachments/assets/84064153-d4df-4643-b4c6-d0477479967a)
4-49bc-bc50-4ff5f83de0e1](https://github.com/user-attachments/assets/c92a7b82-1f8e-4baa-9264-14a15b83f3ac)
![f12dbd62-d8e4-49bc-bc50-4ff5f83de0e1](https://github.com/user-attachments/assets/43c8216a-fb9d-43a6-ad29-05423fee4be8)
![1](https://github.com/user-attachments/assets/d6bf2cad-6e46-42fe-a6b0-afa4c9c134de)

![1](https://github.com/user-attachments/assets/c30453ca-c250-45ee-a755-832ecbbfd1b2)
![2](https://github.com/user-attachments/assets/23a8a41d-a754-4516-b330-e407a1a549d6)
![56b95dd4-4540-490a-bc66-6e9843b36d96](https://github.com/user-attachments/assets/fd3a7c5b-91da-4f22-90e2-43ee7884aa2f)
![9d414947-8bb4-4259-8147-01665bbdd850](https://github.com/user-attachments/assets/1f213b6a-33c7-4b62-a656-2919e4ca7811)
![0662a8f4-7539-4d30-b9f5-b0f777fed579](https://github.com/user-attachments/assets/d0b7a85c-4974-48b4-abfe-c4582a792646)


 This Streamlit application connects to a MySQL database called shop_db and provides a simple interface for viewing and inserting data. It begins by setting up a database connection using SQLAlchemy and implements a basic user authentication system where only predefined users (e.g., "admin" and "user") can log in through a sidebar login form. Once logged in, users can interact with the main interface, which is titled "Data Pipeline with MySQL." The application allows users to select from three database tables—`customers`, orders, and `products`—to view their contents in a formatted table, with an optional filter input for custom SQL WHERE clauses.

Below the data viewer, the app provides a form for inserting new records, specifically into the customers or products table, depending on which one is selected. For the customers table, it collects comprehensive details such as customer number, name, contact info, address, sales representative number, and credit limit. Optional fields like address line 2, state, postal code, sales rep number, and credit limit are handled gracefully by checking if the user provided values or leaving them as NULL if not. If the insertion is successful, the user gets a confirmation message; otherwise, an error is displayed. For products, a simpler form captures the product name and price. Overall, the code offers a user-friendly way to interact with a MySQL database directly through a web interface, with real-time data display and form-based data entry.
