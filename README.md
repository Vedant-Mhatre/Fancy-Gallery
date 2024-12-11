# Fancy Gallery Mobile App

**Developed as an assignment during CS 5254 - Mobile Application Development course at Virginia Tech.**

**Purpose:**  
This app is designed to provide an interactive photo gallery experience, allowing users to browse images fetched from Flickr's API and explore geotagged photo locations on a map.

**Key Features:**

1. **Image Fetching and Display:** Fetches images dynamically from Flickr’s API using Retrofit and Moshi.
2. **Efficient Image Loading:** Integrated Coil for optimized image loading and caching, ensuring smooth scrolling and minimal lag.
3. **Map Integration:** Utilized Google Maps API to display photo locations based on geotagged metadata, enhancing user interaction.
4. **Offline Access:** Implemented Room for local data persistence, enabling users to access photos even without an internet connection.
5. **Optimized Performance:** Focused on efficient image handling and smooth UI transitions for an enhanced user experience.

**Key Learnings:**

1. **API Integration:** How to work with RESTful APIs using Retrofit and parse JSON responses with Moshi.
2. **Image Handling:** How to implement Coil for seamless image loading and caching in a scrollable gallery.
3. **Map Features:** How to integrate Google Maps API and manage geotag data for displaying photo locations.
4. **Data Persistence:** How to use Room to store and retrieve data locally for offline functionality.
5. **UI and UX Design:** How to design a responsive and interactive user interface for a gallery app.
6. **Asynchronous Processing:** How to manage API calls and image loading using Kotlin Coroutines for efficient performance.
