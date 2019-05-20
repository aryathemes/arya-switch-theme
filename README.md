# Switch Theme

Allows users to choose and preview all WordPress themes installed without
activation or deactivation for demonstration purposes.

## Requirements

* PHP version 7.0 or greater
* WordPress 5.0 or greater

## Docker (18.06.0 or greater)

Create and start the container

    docker-compose up -d
    docker exec arya-switch-theme chown -R www-data:www-data /var/www/html
    sudo chown -R $USER:$USER arya-switch-theme

Stop and remove containers, networks, images, and volumes

    docker-compose down --volumes

## Usage

    https://example.com/?theme=slug-theme
    https://example.com/?theme=slug-theme&child=slug-child-theme

## License

This project is licensed under the GNU General Public License, Version 2.0.
See [LICENSE](LICENSE) for the full license text.
