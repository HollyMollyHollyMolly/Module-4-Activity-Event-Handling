# Intermediate Software Development Activity 4

This activity will help to reinforce learning of the Module 4 concepts of:

- Event Handling
- Signals
- Slots
- PySide6

## Author

Nguyen Dang Thai Ha

## Additional Information

- QMainWindow is like the “frame” of your entire app. It comes pre-wired for toolbars, menus, and a central area — just like professional desktop apps (e.g., Photoshop or Qt Designer). You only get one centralWidget, so that’s where your layout lives.

- QLineEdit is a one-liner input box that can handle text, numbers, or even passwords. You can make it mask characters (with setEchoMode) or validate input with setValidator — perfect for things like phone numbers!

- Every QPushButton emits a clicked signal when pressed.
You can connect multiple buttons to the same function — then check which one was clicked using self.sender() if you want fancy behavior.

- QTableWidget is basically a spreadsheet built into Qt.
Each cell isn’t just text — it’s a QTableWidgetItem, which can hold text, icons, tooltips, or even act editable if you allow it. You can also color rows or sort by columns with a single line.

- QTableWidgetItem are little data containers for each cell. Behind the scenes, each one can store not just the display text, but also a “data payload” — useful for IDs or hidden info.

- QLabel isn’t just for text — it can display images, links, or rich HTML.
You could literally make your status label show emojis, colored text, or clickable URLs with .setTextFormat(Qt.RichText).
