# knych-full-stack
![Knych Logo](/logo-knych-white.png) 
<br>
Web App for Funeral Service


## Technology Stack

- **Backend**: Developed using Java, Spring Boot, and MySQL.
- **Frontend**: Built with React (TypeScript) and Vite.
- **Hosting**:
  - Backend is hosted on AWS EC2.
  - Images and frontend are hosted on AWS S3.
  - MySQL database is hosted on AWS RDS.
- **Domain**: Managed through OVH.



## Features

- **Obituaries Management**: Allows the owner to add, edit, and delete obituaries.
- **Obituaries Display**: Obituaries are showcased with pagination and sorting options:
  - By funeral date
  - By death date
- **Candle Tribute**: Users can light a virtual candle for an obituary as a memory tribute.
- **Anniversaries**:
  - Display obituaries of individuals whose death anniversary falls in the current month (but at least a year ago).
  - Pagination and sorting options include:
    - "All" - All obituaries with anniversaries in the current month.
    - "By first name and last name"
    - "By death date"
  - Users can also light a candle for these anniversaries.
- **Grave Search**: Users can access links to search for graves, which can be uploaded and managed by the admin.
- **Dynamic Gallery**: Admin can manage a gallery by adding categories, subcategories, and images. They can also delete these items as needed.
- **Opinions**: Users can leave opinions about the funeral service. Admin approval is required for opinions to be visible, ensuring quality control against potential trolls.
- **Social Sharing**: Users can share obituaries on Facebook with a visually appealing design.
- **Responsive Design**: The application is fully optimized for all device sizes.

## Language

The entire application is developed in Polish, catering to a Polish Knych's service audience.

