    # Enable systemd service
    sudo cp ~/selfhost-seafile/seafile.service /etc/systemd/system/
    sudo systemctl enable seafile.service
    sudo systemctl start seafile.service
