\# MVVM News Application



A modern Android news application built to showcase a robust MVVM architecture, fetching live data from a REST API and persisting data for offline access. This project demonstrates key skills in modern Android development.



!\[App Screenshot](screenshots/news-app-demo.png)  ---



\## Key Features



\- \*\*Live Headlines:\*\* Fetches and displays top headlines from the \[NewsAPI.org](https://newsapi.org) service in real-time.

\- \*\*Search Functionality:\*\* Allows users to search for articles on any topic.

\- \*\*Saved Articles:\*\* Users can save their favorite articles to read later, even without an internet connection.

\- \*\*Web View:\*\* Articles can be opened and read within the app using an integrated WebView.



---



\## Tech Stack \& Architecture



This project is built with a modern technology stack and follows the recommended MVVM architecture pattern.



\- \*\*Language:\*\* Kotlin

\- \*\*Architecture:\*\* MVVM (Model-View-ViewModel)

\- \*\*Asynchronous Programming:\*\* Kotlin Coroutines

\- \*\*Networking:\*\* Retrofit2 for REST API communication

\- \*\*Database:\*\* Room for local data persistence (saving articles)

\- \*\*UI:\*\* XML with Android Views (RecyclerView with DiffUtil)

\- \*\*Navigation:\*\* Jetpack Navigation Component

\- \*\*Image Loading:\*\* Glide



---



\## Setup



To run this project, you need to get your own API key from \[NewsAPI.org](https://newsapi.org).



1\.  Get your free API key from the NewsAPI website.

2\.  Open the project in Android Studio.

3\.  In the `local.properties` file, add the following line:

&nbsp;   `apiKey="YOUR\_API\_KEY\_HERE"`

4\.  Build and run the app.

