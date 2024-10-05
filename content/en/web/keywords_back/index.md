---
title: Keyword and Story Randomized Backend Project
date: 2024-07-01
---

<div class="text-justify">
Project Overview
</div>

Based on Node.js, we developed a back-end service that randomly extracts keywords and stories. The data in the keyword data and storage data folders are provided through APIs, and users can receive randomly extracted data on request.


A major task

- Backend Development: We built an API server with Node.js so that keyword and story data can be extracted at random.
- Data Management: Data from keyword data and storage data folders are used to extract data as needed.
- API Implementation: We designed RESTful API endpoints and provided various random extraction functions to meet user needs.
- Package Management: We used package.json and npm to manage the required packages, and systematically installed and configured the modules of the project.


Technology of use

- Language: JavaScript (Node.js)
- Data management: using datasets within keyworddata, storagedata folders
- Package Management: npm


Performance

- We have built a system that can flexibly handle two datasets (keywords, stories).
- Leveraging the asynchronous processing performance of Node.js, we achieved high performance and response speed.
- API design allows users to efficiently extract data through various requests.