PT & Logistics | Ticket Portal
A client-side web application designed to generate and download travel tickets. Users enter their travel details via a responsive form, and the system instantly renders a digital pass that can be downloaded as an image.
Features
Instant Generation: Form details are dynamically mapped to a professional ticket layout upon submission.
Image Export: Uses html2canvas to let users save their tickets directly to their device as a PNG.
Auto-Timestamp: Captures the exact date and time the booking was issued.
Responsive Design: Clean, mobile-friendly interface built with CSS Grid and Flexbox.
Technical Stack
Frontend: HTML5, CSS3, JavaScript (ES6)
Libraries: html2canvas (via CDN for image rendering)
Typography: Plus Jakarta Sans (via Google Fonts)
How to Deploy on GitHub Pages
Name your main HTML file index.html.
Push your code to a repository on GitHub.
Go to the repository Settings.
In the left sidebar, click Pages.
Under Build and deployment, set the source to Deploy from a branch.
Select your branch (usually main or master) and folder (/root), then click Save.
Your live URL will be ready within a few minutes.
Usage Instruction
Fill out the passenger details, route, vehicle choice, and payment amount.
Click Generate Digital Ticket.
Click Download Ticket (Image) to export the receipt.
Click Book Another Ride to reset the portal.
