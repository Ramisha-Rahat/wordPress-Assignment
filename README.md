<h1>WordPress App - Kotlin Assignment</h1>
This project is a simple WordPress app developed as part of an assignment using Kotlin. The app demonstrates the use of key Android components such as RecyclerView, Adapter, and ViewHolder to display and manage a list of data.

<h3>Features</h3>

<li>RecyclerView: Used to display a scrollable list of WordPress posts.</li>
<li>Adapter: Connects the data to the RecyclerView for rendering each list item.</li>
<li>ViewHolder: Improves performance by reusing views as the user scrolls.</li>
<li>Data Binding: Efficiently binds UI components in the layout to the data source in the app.</li>
<li>Custom Layouts: Each WordPress post is displayed in a custom layout.</li>
<li>Responsive UI: The app is designed to work well on various screen sizes.</li>

Tech Stack
Kotlin: Primary language for the app.
Android SDK: Android development tools and libraries.
RecyclerView: For efficiently displaying scrollable content.
ViewHolder Pattern: For improving performance with RecyclerView.

Project Structure
MainActivity.kt: Entry point of the app. It initializes the RecyclerView and sets the adapter.
PostAdapter.kt: Custom adapter that binds the data to the RecyclerView.
PostViewHolder.kt: ViewHolder class responsible for holding and reusing views.
PostData.kt: A data class representing the WordPress posts being displayed.
