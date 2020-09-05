# siStars-project-1

mydb.db has the structure of our database. It includes:
- a Course table having details of the courses offered (listed 4 courses)
- Vidoes table for each course offered
- Assignments table for each course offered

Note: addition of a new course requires modifications on the backend

## myAdmin.ipynb
It contains functions useful for teachers/admin. Following is the list of functions:
- view_course_details to view details of the courses offered
- select_all_asgnmts to show all assignments of a course
- select_all_videos to show all videos of a course
- add_to_assignments addition of new video in a particular course
- add_to_videos addition of new video in a particular course

## student.ipynb
It contains functions view_course_details, select_all_asgnmts, select_all_videos. In addition to these, it also contains the following functions:
- watch_video to set status of a video of a course as 'YES'(completed)
- do_assignment to set status of a assignment of a course as 'YES'(completed)
