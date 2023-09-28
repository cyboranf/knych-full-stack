# knych-full-stack
Web Application for Funeral Service

### Features

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
- **Opinions**: Users can leave opinions about the funeral service. Admin approval is required for opinions to be visible, ensuring quality control against potential trolls.
- **Responsive Design**: The application is fully optimized for all device sizes.

### Technology Stack

- **Backend**: Developed using Java, Spring Boot, and MySQL.
- **Frontend**: Built with React (TypeScript) and Vite.
- **Hosting**:
  - Backend is hosted on AWS EC2.
  - Images and frontend are hosted on AWS S3.
  - MySQL database is hosted on AWS RDS.
- **Domain**: Managed through OVH.
