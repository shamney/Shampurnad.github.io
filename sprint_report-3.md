## What's New (User Facing)

Two-Factor Authentication (2FA) implemented via email OTP
Dynamic inventory dashboard with yellow/red alarms for thresholds and expiry
Weekly/monthly/product-wise chart visualizations (line, pie, bar, histogram)
Admin-only threshold management interface with edit/delete options
User login, signup, and password recovery with email reset link
Functional filtering and editing of inventory items
Visual inventory alerts based on low quantity or expired products
Work Summary (Developer Facing)

During this sprint, our team focused on completing core inventory workflows and implementing full-stack testing coverage. We broke down the work into backend (Django models and views), frontend (HTML/CSS templates and chart rendering), and security (2FA and password reset). One of the key challenges was integrating interactive data visualization using Chart.js while ensuring backend chart data was correctly grouped and filtered. We also implemented threshold-based alerts with customizable messages and color-coded warnings. Our team held weekly meetings with the professor, which helped us realign tasks and clarify sprint objectives. Selenium testing and Django unit tests were run to validate login, 2FA, and inventory workflows.

## Unfinished Work

I was not able to fully implement the feature for downloadable/exportable reports (e.g., PDF or CSV) from the dashboard due to time constraints.
Progress has been tracked and commented on GitHub, and this feature has been added to the next sprint for follow-up.

## Completed Issues/User Stories

Implement 2FA email OTP system
Build inventory overview with color alerts
Create product-wise dashboard with filters
Implement threshold edit/delete for admin
Add password reset via email link

## Incomplete Issues/User Stories

Export reports to PDF/CSV – I ran out of time after prioritizing security and dashboard integration
Add email notifications for low stock – Backend logic implemented but email templates not finished

## Code Files for Review

views.py
threshold_list.html
tests_selenium.py
Retrospective Summary

## What went well:
Good teamwork and consistent progress across sprints
Weekly feedback from professor was highly valuable
2FA and chart visualizations were completed successfully
What we’d like to improve:
Spend more time estimating difficulty of tasks
Split frontend and backend tasks earlier in the sprint
Better time allocation for final testing and polish

## Plans for the next:
Implement report export (PDF/CSV)
Add user roles for employees/volunteers
Optimize chart data queries for large datasets
