# **TCX Lap Editor**

A simple, fast, and privacy-focused web tool for editing and concatenating laps in your Garmin .tcx fitness activity files.

## **Problem Solved**

Did your sports watch accidentally "auto-lap" during a segment run or bike ride? This tool allows you to:

* **Merge Laps:** Combine multiple split laps into one single lap while recalculating distance, time, and heart rate data correctly.  
* **Delete Laps:** Remove accidental laps.  
* **Edit Metadata:** Adjust lap intensity (Active/Resting) directly in your browser.

## **Features**

* **Privacy First:** All processing happens locally in your browser. Your TCX files are never uploaded to a server or stored in the cloud.  
* **Data Integrity:** Calculates time-weighted averages for Heart Rate and correctly aggregates GPS Trackpoint data during merges.  
* **Simple UI:** Built with Bootstrap for a clean, responsive, and easy-to-use interface.  
* **No Dependencies:** No installation required. Just open the HTML file and start editing.

## **How to Use**

1. Clone or download this repository.  
2. Open tcx-editor.html in any modern web browser (Chrome, Firefox, Edge, Safari).  
3. Click **"Upload Workout"** and select your .tcx file.  
4. Select the laps you wish to edit using the checkboxes.  
5. Click **"Merge Selected"** or **"Delete Selected"**.  
6. Click **"Download Modified TCX"** to save your corrected activity file.

## **Technical Details**

* **Frontend:** HTML5, Bootstrap 5\.  
* **Logic:** Vanilla JavaScript with DOMParser for XML manipulation.  
* **Compatibility:** Works with standard Garmin Training Center XML (TCX) schemas.

## **License**

This project is open-source and free to use.

*Created as a solution for quick fitness data cleanup.*