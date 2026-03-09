# Moodle Installation Instructions

You need:
- The hardware to run Moodle on
- The Moodle program files
- A supported HTTP server
- A supported database

Moodle has a detailed [installation guide](https://docs.moodle.org/501/en/Installing_Moodle) available. Please follow this guide to install Moodle. **Important: Moodle version >=5.1 is required**

The course was developed using Moodle 5.1, but is expected to run on future versions. I recommend checking which version (>=5.1) is currently supported on the [releases page](https://moodledev.io/general/releases) and using that one.

Apart from the default installation, you may need to do the following to run the course:
1. Install the German language pack for the UI, please see the [language pack installation guide](https://docs.moodle.org/501/en/Language_packs).
2. Increase the upload file size according to the [upload file size guide](https://docs.moodle.org/501/en/File_upload_size). I recommend at least 16MB.
3. Set up the [cron process](https://docs.moodle.org/501/en/Cron), if not already done during the installation.

# Import of the Course

After the installation is complete:

1. Go to "Site Administration" -> "Course" -> "Restore Course"
2. Upload the .mbz file to import and click "restore".
3. Review the data to import, and click "continue" at the bottom of the page.
4. Select "Restore as a new course" and select the category to import the course into. This can stay the default catergory "Category 1". Click "continue" in the "Restore as a new course" section.
5. On the "restore settings" page, select everything and click "next".
6. On the "course settings" page, select everything and click "next".
7. On the next page (5. Review), scroll to the bottom and click "perform restore".
