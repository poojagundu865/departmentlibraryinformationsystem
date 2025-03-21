
# Department Library Information System

A comprehensive library management system designed for the Department of Computer Science & Engineering. This system allows students to browse, search, and request books, while administrators can manage the library collection, handle book requests, and track availability.

## Features

### For Students
- **Browse Library Collection**: View all books with cover images, titles, and authors
- **Search Functionality**: Search for books by title, author, or category
- **Book Details**: View detailed information about each book
- **Request Books**: Submit requests to borrow books from the library
- **Track Requests**: Monitor the status of book requests
- **Provide Feedback**: Submit feedback to library administrators

### For Administrators
- **Manage Book Requests**: Approve or reject student book requests
- **Library Collection**: View and manage the entire book collection
- **Add New Books**: Add new books to the library database
- **Monitor Metrics**: View stats on total books, available books, and active requests
- **View Feedback**: Review feedback submitted by students

## Technology Stack

- **Frontend**: React, TypeScript, Tailwind CSS
- **State Management**: React Context API, React Query
- **UI Components**: ShadCN UI, Framer Motion
- **Routing**: React Router
- **Notifications**: Sonner
- **Icons**: Lucide React

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/library-system.git
   cd library-system
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm run dev
   ```

4. Open your browser and navigate to `http://localhost:5173`

## Usage

### Login Credentials

#### Student Access
- Username: `student`
- Password: `password`

#### Admin Access
- Username: `admin`
- Password: `password`

## Project Structure

```
src/
├── components/       # Reusable UI components
├── pages/            # Page components 
├── hooks/            # Custom React hooks
├── utils/            # Utility functions
├── lib/              # Library code
├── App.tsx           # Main application component
├── main.tsx          # Application entry point
```

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgements

- Department of Computer Science & Engineering
- All contributors and maintainers
