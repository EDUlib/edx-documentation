.. _Enabling and Configuring Cohorts:

############################################
Enabling and Configuring the Cohorts Feature
############################################

If you want to use cohorts in your course, you select a strategy for assigning
your students to cohorts: automated assignment, manual assignment, or a hybrid
approach. Although you can change the assignment method for cohorts at any time,
you should have a strategy in mind as you design your course, and only make
changes to cohorts while the course is running if absolutely necessary. See
:ref:`Options for Assigning Students to Cohorts`.

You also decide whether course-wide and content-specific discussion topics
should be divided by cohort or unified for all students.

After you decide on a cohort strategy for your course, you complete these
configuration steps (as applicable).

#. :ref:`Enable cohorts<Enable Cohorts>`.

#. Determine the method you want to use to assign students to cohorts:
   
  * :ref:`Implement an automated assignment strategy<Implementing the Automated
    Assignment Strategy>`

  * :ref:`Implement a manual assignment strategy<Implementing the Manual
    Assignment Strategy>` and :ref:`manually assign students<Assign Students to
    Cohorts Manually>` to the cohorts you create

  * :ref:`Use a combination of automated and manual assignment<Hybrid
    Assignment>`

3. Optionally, identify the discussion topics that you want to be divided by
   cohort.
   
  * If you want :ref:`course-wide discussion topics to be divided by
    cohort<Identifying Private CourseWide Discussion Topics>`, you need to complete
    some configuration tasks.

  * In contrast, if you want content-specific discussion topics to be divided
    by cohort, you do not need to take any action. Instead, you need to complete
    some configuration tasks only if you want :ref:`content-specific discussion
    topics to be unified<Make ContentSpecific Discussion Topics Unified>`.

You complete these procedures on the **Cohort Management** tab on the Instructor Dashboard. 

For an optimal student experience, you should make sure that configuration of
the cohort feature is as complete as possible prior to the start date of your
course. If you need to make changes to the way you have configured cohorts while
your course is running, be aware of the implications of your changes. For more
information, see :ref:`Altering Cohort Configuration`.


.. _Implementing the Automated Assignment Strategy:

***************************************************
Implementing an Automated Assignment Strategy
***************************************************

To implement an automated assignment strategy of students to cohorts, you
:ref:`enable the cohort feature<Enable Cohorts>` for your course, and
:ref:`create cohorts<Add Cohorts>` to which students are automatically and
randomly assigned.

For a scenario using an automated assignment strategy, see :ref:`All Automated
Assignment`. For a scenario using a combination of automated and manual
assignment to cohorts, see :ref:`Hybrid Assignment`.

.. note:: You can add students manually to any cohort, whether it was created as
   an automated cohort or a manual cohort.


.. _Implementing the Manual Assignment Strategy:

***************************************************
Implementing a Manual Assignment Strategy
***************************************************

To implement a manual assignment strategy of students to cohorts, you
:ref:`enable the cohort feature<Enable Cohorts>` for your course, and :ref:`create
cohorts<Add Cohorts>` to which you manually assign students.

For a scenario using a manual assignment strategy, see :ref:`All Manual
Assignment`. For a scenario using a combination of automated and manual
assignment to cohorts, see :ref:`Hybrid Assignment`.

.. note:: You can add students manually to any cohort, whether it was created as
   an automated cohort or a manual cohort.


.. _Enable Cohorts:

*********************************
Enabling Cohorts in your Course
*********************************

To enable cohorts in your course, follow these steps.

#. In the LMS, select **Instructor**, then select **Cohort Management**. 

#. Select **Enable Cohorts**.
   
You can now implement the cohort strategy for your course by :ref:`adding
cohorts<Add Cohorts>`.


.. _Add Cohorts:

****************
Adding Cohorts
****************

After you enable the cohorts feature for your course, you can add cohorts.

#. In the LMS, select **Instructor**, then select **Cohort Management**.

#. Click **Add Cohort**.

#. Enter a name for the cohort.

.. note:: Students can see the name of the cohort they are assigned to. The
   message "This post is visible only to {cohort name}" appears with each post
   in discussion topics that are divided by cohort. See :ref:`Read the Cohort
   Indicator in Posts`.

#. Specify whether students are automatically or manually assigned to this
   cohort.
   
#. Optionally, select **Select a Content Group** to associate the cohort with a
   :ref:`content group<About Content Groups>`. For information about creating
   cohort-specific courseware by associating cohorts with content groups, see
   :ref:`Cohorted Courseware Overview`.

#. Click **Save**. 
   
Continue implementing your cohort strategy by creating additional cohorts as
applicable, and specifying manual or automatic assignment method for each
cohort.

For details about adding students to a cohort by uploading a .csv file, see
:ref:`Assign Students to Cohort Groups by uploading CSV`/

.. note:: When your course starts, you must have at least one cohort in your
   course that has automatic assignment. If you have not created at least one
   automated assignment cohort in the course by the time that the first student
   accesses your course content, edX creates a default cohort to which students
   are automatically assigned.

For a report that includes the cohort assignment for every enrolled
student, review the student profile information for your course. See
:ref:`View and download student data`.

.. note:: You cannot delete cohorts, but you can change their names or the way
   in which students are assigned to them. If you need to make changes to the
   way you have configured cohorts while your course is running, see
   :ref:`Altering Cohort Configuration`.
   

.. _About Auto Cohorts:

=================
Automated Cohorts
=================

.. note:: When your course starts, you must have at least one cohort in your
   course that has automatic assignment. If you have not created at least one
   automated assignment cohort in the course by the time that the first student
   accesses your course content, edX creates a default cohort to which students
   are automatically assigned.

The first time a student first views any course content, including the course
**Discussion** page or content-specific discussion topics, if she is not already
assigned to a cohort, she is randomly assigned to one of the automated cohorts.
If no automated cohorts exist, the system creates a :ref:`default cohort` and
assigns the student to this default cohort.

For a report that includes the cohort assignment for every enrolled student,
review the student profile information for your course. See :ref:`View and
download student data`.


.. _About Manual Cohorts:

==============
Manual Cohorts
==============

.. note:: Manual assignments should be as complete as possible before your
   course starts. If student enrollment continues after your course starts, you
   should continue to assign new students to cohorts. If you need to make
   changes to the way you have configured cohorts while your course is running,
   see :ref:`Altering Cohort Configuration`.

For a report that includes the cohort assignment for every enrolled student,
review the student profile information for your course. See :ref:`View and
download student data`.


.. _Assign Students to Cohort Groups by uploading CSV:

========================================================
Assign Students to Cohorts by Uploading a .csv File
========================================================

In addition to assigning students to cohorts by entering usernames or email
addresses directly on the Cohort Management page in the Instructor Dashboard,
you can also upload a .csv file containing a list of students and the cohorts
that you want to assign them to.

Any assignments to cohorts that you specify in the .csv files you upload
will overwrite or change existing cohort assignments. The configuration of
your cohorts should be complete and stable before your course begins. You
should also complete manual cohort assignments as soon as possible after any
student enrolls, including any enrollments that occur while your course is
running. To understand the effects of changing cohort assignments after your
course has started, see :ref:`Altering Cohort Configuration`.

.. note:: Be aware that the contents of the .csv file are processed row by row,
  from top to bottom, and each row is treated independently. 

  For example, if your .csv file contains conflicting information such as
  Student A being first assigned to Cohort 1, then later in the spreadsheet
  being assigned to Cohort 2, the end result of your .csv upload is that Student
  A is assigned to Cohort 2. However, the upload results file will count Student
  A twice in the "Students Added" count: once when they are added to Cohort 1,
  and again when they are added to Cohort 2. Before submitting a file for
  upload, check it carefully for errors.

The requirements for the .csv file are summarized in this table.

.. list-table::
    :widths: 15 30

    * - **Requirement**
      - **Notes**
    * - Valid .csv file

      - The file must be a properly formatted comma-separated values file: 

        * The file extension is .csv.
        * Every row must have the same number of commas, whether or not there
          are values in each cell. 
    * - File size
      - The file size of .csv files for upload is limited to a maximum of 2MB.               
    * - UTF-8 encoded
      
      - You must save the file with UTF-8 encoding so that Unicode characters
        display correctly. 

        See :ref:`Creating a Unicode Encoded CSV File`.

    * - Header row
      - You must include a header row, with column names that exactly match those 
        specified in "Columns" below.
    * - One or two columns identifying students      
      - You must include at least one column identifying students: 
        either "email" or "username", or both. 

        If both the username and an email address are provided for a student,
        the email address has precedence. 
        
        In other words, if an email address is present, an incorrect or non-
        matching username is ignored.

    * - One column identifying the cohort
            
      - You must include one column named "cohort" to identify the cohort
        to which you are assigning each student.

        The specified cohorts must already exist in Studio.

    * -                        
      - Columns with headings other than "email", "username" and "cohort" are
        ignored.

Follow these steps to assign students to cohorts by uploading a .csv file.
      
#. View the live version of your course. For example, in Studio, click **View
   Live**.

#. Click **Instructor**, then click **Cohort Management**. 

#. In the dropdown list of cohorts, select the cohort to which you are adding
   students.

#. Click **Assign students to cohorts by uploading a CSV file**, then click
   **Browse** to navigate to the .csv file you want to upload.

#. Click **Upload File and Assign Students**. A status message displays
   above the **Browse** button.

#. Verify your upload results on the **Data Download** page. 

   Under **Reports Available for Download**, locate the link to a .csv file with
   "cohort_results" and the date and time of your upload in the filename. The
   list of available reports is sorted chronologically, with the most recently
   generated files at the top.

The results file provides the following information:  

.. list-table::
    :widths: 15 30

    * - **Column**
      - **Description**
    * - Cohort
      - The name of the cohort to which you are assigning students.
    * - Exists
      - Whether the cohort was found in the system. TRUE/FALSE. 
      
        If the cohort was not found (value is FALSE), no action is taken for students you assigned to that cohort in the .csv file.

    * - Students Added
      - The number of students added to the cohort during the row by row
        processing of the .csv file.             
    * - Students Not Found
      - A list of email addresses or usernames (if email addresses were not
        supplied) of students who could not be matched by either email address
        or username and who were therefore not added to the cohort.
             
For a report that includes the cohort assignment for every enrolled student,
review the student profile information for your course. See :ref:`View and
download student data`.


.. _Creating a Unicode Encoded CSV File:

====================================
Creating a Unicode-encoded .csv File
====================================

Make sure the .csv files that you upload are encoded as UTF-8, so that any
Unicode characters are correctly saved and displayed.

.. note:: Some spreadsheet applications (for example, MS Excel) do not allow you
   to specify encoding when you save a spreadsheet as a .csv file. To ensure that
   you are able to create a .csv file that is UTF-8 encoded, use a spreadsheet
   application such as Google Sheets, LibreOffice, or Apache OpenOffice.


.. _Altering Cohort Configuration:

*************************************************
Altering Cohort Configuration in a Running Course
*************************************************

The configuration of cohorts in your course should be complete and stable before
your course begins. Manual cohort assignments should be completed as soon as
possible after any student enrolls, including any enrollments that occur while
your course is running.

If you decide that you must alter cohort configuration after your course starts
and activity in the course discussion begins, be sure that you understand the
consequences of these actions. 

* :ref:`Changing Student Cohort Assignments`
* :ref:`Renaming a Cohort`
* :ref:`Deleting a Cohort`
* :ref:`Changing the Assignment Method of a Cohort`
* :ref:`Disabling the Cohort Feature`


.. _Changing Student Cohort Assignments:

=================================
Change Student Cohort Assignments
=================================

After your course starts and students begin to contribute to the course
discussion, each post that they add is visible either to everyone or to the
members of a single cohort. When you change the cohort that a student is
assigned to, there are three results:

* The student continues to see the posts that are visible to everyone.

* The student sees the posts that are visible to his new cohort.

* The student no longer sees the posts that are visible only to his original
  cohort.

The visibility of a post and its responses and comments does not change, even if
the cohort assignment of its author changes. To a student, it can seem that
posts have "disappeared".

To verify the cohort assignments for your students, download the  :ref:`student
profile report<View and download student data>` for your course. If changes are
needed, you can :ref:`assign students<Assign Students to Cohorts Manually>` to
different cohorts manually on the **Cohort Management** page of the Instructor
Dashboard, or :ref:`upload cohort assignment changes<Assign Students to Cohort
Groups by uploading CSV>` in a .csv file.


.. _Renaming a Cohort:

===============
Rename a Cohort
===============

You can change the name of any cohort, including the system-created default
cohort.

To rename a cohort, follow these steps.

#. View the live version of your course. For example, in Studio click **View
   Live**.

#. Click **Instructor**, then click **Cohort Management**. 

#. From the drop down list, select the cohort whose name you want to change.

#. On the **Settings** tab, in the **Cohort Name** field, enter a new name for
   the cohort.

#. Click **Save**. The name for the cohort is updated throughout the LMS and the
   courseware, including student-visible views.


.. _Deleting a Cohort:

================
Delete a Cohort
================

Deletion of cohorts is not supported. However, it is possible to :ref:`rename a
cohort<Renaming a Cohort>`, :ref:`change its assignment method <Changing the
Assignment Method of a Cohort>`, or move students to other cohorts, instead of
deleting a cohort.

If you decide that you must alter cohort configuration after your course starts
and activity in the course discussion begins, be sure that you understand the
consequences of these actions. For more details, see :ref:`Altering Cohort
Configuration`.


.. _Changing the Assignment Method of a Cohort:

==========================================
Changing the Assignment Method of a Cohort
==========================================

Although you can change the assignment method of a cohort at any time after you
create it, you should have a strategy in mind as you design your course, and
only make changes to cohorts while the course is running if absolutely
necessary. Be aware of the implications of changing cohort configuration while
your course is running. For more information, see :ref:`Options for Assigning
Students to Cohorts` and :ref:`Altering Cohort Configuration`.

.. note:: When your course starts, you must have at least one cohort in your
   course that has automatic assignment. If you have not created at least one
   automated assignment cohort in the course by the time that the first student
   accesses your course content, edX creates a default cohort to which students are
   automatically assigned. If the :ref:`Default Group<Default Cohort Group>` is the
   only automated assignment cohort in your course, you cannot change its
   assignment method to **Manually Assigned**.

To change the assignment method of a cohort, follow these steps.

#. View the live version of your course. For example, in Studio click **View
   Live**.

#. Click **Instructor**, then click **Cohort Management**. 

#. From the drop down list, select the cohort whose assignment method you want
   to change.

#. On the **Settings** tab, the current assignment method is selected. Change
   the assignment method by selecting the other option, either **Automatically
   Assigned** or **Manually Assigned**.

#. Click **Save**. 

   The cohort assignment method is updated. When you refresh the page, the new
   cohort assignment method for the cohort is selected.

.. note:: Changing the cohort assignment method has no effect on students who
   are already assigned to this and other cohorts in your course. Students who
   access the course after you make this change are assigned to cohorts based on
   the new assignment method of this cohort combined with the assignment methods
   of all other cohorts in your course.


.. _Disabling the Cohort Feature:

==========================
Disable the Cohort Feature
==========================

To disable cohorts in your course, follow these steps.

#. In the LMS, select **Instructor**, then select **Cohort Management**. 

#. Clear the **Enable Cohorts** option.
   
All discussion posts and course content that was previously divided by cohort
immediately become visible to all students.

If you re-enable the cohort feature after disabling it, all previous student
cohort assignments are reenabled, and all visibility settings for posts and
courseware are re-applied. However, any posts created while the cohort feature
was disabled are not divided by cohort, and  remain visible to all users.
