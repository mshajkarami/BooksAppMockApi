# Books App (Mock API)

A simple and clean Android app showcasing a list of books using a mock API. This app is designed for prototyping, UI testing, and architecture demonstrations without relying on a real backend.

## 📚 Features

- Fetch and display books from a mock API
- View book details
- Clean and modular codebase
- MVVM architecture with Repository pattern
- Works entirely offline with local JSON or mock server

## 🧰 Tech Stack

- **Language:** Kotlin  
- **Architecture:** MVVM  
- **UI:** RecyclerView, ViewBinding  
- **Mock API:**  
  - Local JSON file or Retrofit with MockInterceptor  
  - Optionally using [MockWebServer](https://square.github.io/okhttp/mockwebserver/) for testing  
- **Other:** LiveData, ViewModel, Coroutines

## 🗂️ Project Structure

```text
com.yourpackage.booksapp/
│
├── data/               # Repository and data sources
├── model/              # Data classes (Book, Author, etc.)
├── network/            # Mock API setup (e.g., MockInterceptor)
├── ui/                 # Activities and Fragments
├── utils/              # Helper classes and extensions
└── viewmodel/          # MVVM logic

```

🚀 Getting Started
Clone the project:
git clone https://github.com/your-username/BooksAppMockApi.git

Open in Android Studio and run on an emulator or device.

Optional: Use with MockWebServer
If using MockWebServer, make sure to include test JSON files and initialize the server before running API calls.

📄 License
This project is licensed under the MIT License – see the LICENSE file for details.
