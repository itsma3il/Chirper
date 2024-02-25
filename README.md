# Chirper Application

Chirper is a simple social media application where users can post short messages known as "chirps" and interact with other users by following them and liking their chirps.

## Features

- **User Authentication**: Users can sign up, log in, and log out securely.
- **Chirp Creation**: Authenticated users can create and post chirps.
- **Chirp Interaction**: Users can like and comment on chirps.
- **User Profiles**: Each user has a profile page displaying their chirps and followers.
- **Follow/Unfollow**: Users can follow and unfollow other users to see their chirps in their feed.
- **Notifications**: Users receive notifications for new likes and comments on their chirps.
- **Search**: Users can search for other users and chirps.

## Technologies Used

- **Backend**: Laravel (PHP)
- **Frontend**: HTML, CSS (with Tailwind CSS), JavaScript
- **Database**: SQLite
- **Authentication**: Laravel Passport (OAuth2)
- **Real-time Updates**: Pusher or Laravel Echo (optional for real-time notifications)

## Setup Instructions

1. **Clone the Repository**: `git clone https://github.com/yourusername/chirper.git`
2. **Install Dependencies**: `composer install` (for Laravel)
3. **Set Up Environment Variables**: Copy the `.env.example` file to `.env` and configure database settings, app key, etc.
4. **Run Migrations**: `php artisan migrate` (to create database tables)
5. **Start Development Server**: `php artisan serve` (for local development)
6. **Optional**: Set up Pusher or Laravel Echo for real-time notifications (if applicable)

## Contributing

Contributions are welcome! If you'd like to contribute to Chirper, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/my-feature`).
3. Make your changes and commit them (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature/my-feature`).
5. Create a new Pull Request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- This project was inspired by Twitter and other social media platforms.
- Special thanks to the Laravel community for providing excellent documentation and resources.
