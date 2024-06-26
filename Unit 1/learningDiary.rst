.. submitted already to AU for assessment, file locked 25 MAY 2024

Site design
++++++++++++

.. _unit1-ref:

Summary
========

    *"I took my time to complete this unit to make purposeful decisions. They save me time later when completing the coding in later units. I wrote .html with future scripts and styling in mind, leaving my mock up to be a very baremetal with an emphasis on the sitemap. My site is built to suit my personas and their scenarios."*


The work
==========
.. describe briefly what you have done as work for that unit.


1. Visit `AU course book <https://scis.lms.athabascau.ca/mod/book/view.php?id=13059>`_ > **print book** as .pdf for offline reading.

2. Read the 19 instruction pages.

    .. Note::
       The Unit 1 reading markup is provided as an attachment under **References**.

3. Prepare the design documentation.

   - Theme and purpose
   - Personas
   - Scenarios
   - Further requirements
   - Mockup
   - Site map
   - Learning diary

4. Upload the documentation to GitHub and submit a learning diary post as a blog entry in the **Group Blog**.

5. Notify the tutor of the submission, and upload to the **AU drop box**.



Assignment 1 submission
========================
.. describe the rationale for what you have done, relating your work explicitly to the personas and scenarios you developed in Unit 1.

Theme and purpose
------------------

   *A website to document some tools I made for technical publication specialists, like a portfolio and download hub. The website showcases free tools that can be used in a variety of workflows. Users can use this site to automate processes, learn, or get inspiration to write their own CRUD tools.*


I think this is useful because it helps others who don't have the time to dig into the *hours* of debugging required to write some of these tools, or those who may not have the programming background to do it themselves. 


My audience is a pool of ~27,000+ technical writers, editors, copywriters, product managers, knowledgebase specialists, developer advocates, solutions architects, and really anyone involved in data, scientific, product, or knowledge publications. They are collected in subreddits and communities that I belong to. 

There is a growing number of these professionals who are currently being trapped by outdated learning resources hidden behind a pay wall.

   *My goal is to provide knowledge and valuable upskilling for free, while demonstrating how a technical writer could 10x productivity.*
   

The scope for this build is realistic and well thought. I have a variety of tools that I've programmed in javascript, but I lack the front-end know-how to present them in a captivating way. I am looking to leverage some frameworks in unit 6, though I saw I'll need to also at least submit one JQuery solution as well:

+ `chart.js <https://gsap.com/>`_
+ `GSAP <https://gsap.com/>`_
+ `d3.js <https://d3js.org/>`_
+ `three.js <https://threejs.org/>`_

With these ideas, I can keep my site focused primarily on publication through the documentation of my tools, while doing it in a dynamic way with forms, actions, animations, conversions, sorts, multimedia control, etc.



Personas and scenarios
------------------------
I made sure to prepare a future-proof way of managing my personas, which are important because they dictate a lot of the compliant code I will need to write to make the site responsive and compliant with AODA requirements for accessibility.

I used a :download:`.csv for the data <../attachments/personaData.csv>`, and an :download:`.indd file for the publishing <../attachments/personaMain.indd>` template. Since I know that this can change in future, I want to make sure I have an easy way to edit the source data and re-publish the .pdf's quickly. The way I have designed this has automated this process for me, since the template accepts the persona data as variables, managed from the .csv.


Read my personas **with their scenarios** `here <https://github.com/hectorbarquero/university-COMP266/tree/main/attachments/personas>`_

.. image:: ../images/peter.jpg
   :alt: Persona of Peter

.. image:: ../images/lena.jpg
   :alt: Persona of Lena

.. image:: ../images/priya.jpg
   :alt: Persona of Priya

.. image:: ../images/simran.jpg
   :alt: Persona of Simran

.. image:: ../images/john.jpg
   :alt: Persona of John
   
.. image:: ../images/leeanne.jpg
   :alt: Persona of Lee-anne



Further requirements
---------------------
I considered a few legal obligations and browsed similar products to determine I need the following:

+ Accessibility compliance statement
+ Canadian consumer protection laws
+ Anti spam
+ Open source license declaration
+ Security declaration for trust
+ Third-party software acknowledgement
+ Respect for third-party licenses
+ Privacy and data protection notices
+ Warnings to remove liability for potential data
+ System corruption when running any of the tools
+ Notifications and consent

Source more information about these Canadian e-Commerce requirements `on this web page <https://sbs-spe.feddevontario.canada.ca/en/e-business-security-privacy-and-legal-requirements>`_.


Mock up and site map
---------------------
My site map is available here as both `.xml <https://github.com/hectorbarquero/university-COMP266/blob/main/attachments/siteMap.drawio>`_ and a `.png <https://github.com/hectorbarquero/university-COMP266/blob/main/images/COMP266sitemap.png>`_. 

It contains:

+ The typical user journey
+ The navigation choices
+ Pages within the navigation choices
+ The connections between some, where an excerpt exists
+ The external flows to other technologies powering some of the features, which the AU server can't power reliably


.. image:: ../images/COMP266sitemap.png
   :alt: Site map of my project.


To see it all connected, check out my mock up. You can also `view these on my GitHub <https://github.com/hectorbarquero/university-COMP266/tree/main/images/mockup>`_ to view them individually.


.. image:: ../images/mockup/COMP266welcome.png
   :alt: Mock up of the initial welcome pages

.. image:: ../images/mockup/COMP266testimonials-footer.png
   :alt: Mock up of the footer including testimonials

.. image:: ../images/mockup/COMP266showcase-downloads.png
   :alt: Mock up of the tools section

.. image:: ../images/mockup/COMP266about-faq-contact.png
   :alt: Mock up of the final page, contact and about information


The learning map
=================
.. for each learning outcome for the unit, explain how you have met it, with reference to the content that you produce (typically your code or other design artifacts).

Find the rubric here and grade my work here:


Expected outcomes for Unit 1
-----------------------------

1. This unit required me to identify the potential audience and purpose for a website. 
2. This unit required me to use a simple but structured process to identify how the website will address the needs of the anticipated audience.

See the AU rubric, and compare my design files against these expectations.


What went right and wrong
==========================
.. describe what you would do differently if you had to do it again.

   I am happy with the the work I did. If I were to do it again, not a lot would be done differently. 

One issue that was plaguing me was the .pdf builder for my project. In short, there is no cache busting on my server. To temporarily fix this, I give the DNS cache approximately 24 hours to resolve CDN issues itself. I withheld .pdf submissions from my learning diary posts on the AU landing, and leave those .pdf submissions for the drop-box instead.

The simplest way to submit assignments would be to use a standard text editor and generate a .pdf with the built-in .pdf exporter engine. 

I opted to use a different solution, especially for my personas, because the imminent future maintainability of this project is on my mind. The instructions noted that we should choose something that we're passionate about, and something that we could see ourselves working on for months or years.

In those months and years, I think my complicated debugging will feel nominal for the value added gain of ease of maintenance. 


Additional reading
===================

+ :download:`COMP 266 - Unit 1 orientation notes <../attachments/readings/unit1Reading.pdf>`
+ `Learning diary <https://github.com/hectorbarquero/university-COMP266>`_
+ :ref:`Unit 0 learning diary <unit0-ref>`


Get in touch
=============

I don't check my emails often. Connect with me on `LinkedIn <https://www.linkedin.com/in/hectorbarquero>`_, or see what I'm up to on `GitHub <https://github.com/hectorbarquero>`_.

