# Ska - Front-End for Chemsheets/Scisheets and Exam Papers Practice (EPP)

This project provides the front-end for accessing files on [Chemsheets/Scisheets](https://www.scisheets.co.uk/) and [Exam Paper Practice](https://www.exampaperspractice.co.uk/). The backend API can be used to retrieve media files, but there are concerns regarding the accessibility of paid content. It is suggested that better security measures be implemented to prevent unauthorised access.

## How to Use

1. **Check Your Own Chemsheets/EPP File:**
   * Get the Chemsheets/EPP file you have.
   * Note its file name.

2. **Use Ska to Find Your File:**
   * Visit [Ska](https://wezlemin.github.io/ska/).
   * Enter the file name.
   * That's all!

## API Endpoint

To access media files on Scisheets, use the following endpoint:

```
https://scisheets.co.uk/wp-json/wp/v2/media?per_page=(1-100)&page=(1-308)
```

* **per_page**: Number of files per page (1-100)
* **page**: Page number (1-308)

To access media files on EPP, use the following endpoint:

```
https://www.exampaperspractice.co.uk/wp-json/wp/v2/media?per_page=(1-100)&page=(1-3976)
```

* **per_page**: Number of files per page (1-3976)
* **page**: Page number (1-3976)

## Takedown Requests

For takedown requests, contact:

**Email**: [wezlemington@outlook.com](mailto:wezlemington@outlook.com)
