# Music PLayList Manager.V.1.2
This system is a Music Playlist Manager that allows users to manage and organize a playlist of songs. It includes functionalities for adding, removing, sorting, searching, and displaying songs, as well as saving and loading playlists from files. Additionally, the system supports undo and redo actions, as well as a priority queue for managing top-rated songs. Below are the key features and uses of the system:
Key Features:
1.	Add Song: You can add songs to the playlist, and optionally add them to a priority queue as well.
2.	Remove Song: You can remove a song by its title, and it has undo/redo capabilities.
3.	Display Playlist: You can display all songs in the playlist, sorted by rating or filtered by a specific rating.
4.	Search Song: You can search for a song by its title (case-insensitive).
5.	Undo/Redo: Supports undoing and redoing actions (such as adding or removing a song).
6.	Priority Queue: Songs can be added to a priority queue, and the top-rated songs can be displayed in the order of their rating.
7.	File Handling: The program supports loading from and saving to text files for both the playlist and the priority queue.
The system is designed to provide users with full control over their music playlists, with features for managing song information, sorting, searching, and ensuring changes can be easily undone. It also offers file storage, making it easy to save and share playlists. The priority queue provides an efficient way to manage top-rated songs, adding a layer of convenience for music lovers.

Summary of Algorithms:
Operation	Algorithm	Time Complexity
Add song to playlist	Insertion at the end	O(1)
Remove song from playlist	Linear Search + Delete	O(n)
Search for a song	Linear Search	O(n)
Sort playlist by rating	Bubble Sort / Selection Sort	O(n²)
Display all songs	Linear Traversal	O(n)
Undo/Redo action	Stack-based undo/redo	O(1)
