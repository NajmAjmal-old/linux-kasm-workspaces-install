# Kasm workspaces Install command

> Note: This requires at least 4gb of ram


    cd /tmp
    curl -O https://kasm-static-content.s3.amazonaws.com/kasm_release_1.14.0.7f3582.tar.gz
    tar -xf kasm_release_1.14.0.7f3582.tar.gz
    sudo bash kasm_release/install.sh

# Kasm workspaces Install command (arm64)

    cd /tmp
    curl -O https://kasm-static-content.s3.amazonaws.com/kasm_release_1.14.0.7f3582.tar.gz
    curl -O https://kasm-static-content.s3.amazonaws.com/kasm_release_service_images_arm64_1.14.0.7f3582.tar.gz
    curl -O https://kasm-static-content.s3.amazonaws.com/kasm_release_workspace_images_arm64_1.14.0.7f3582.tar.gz
    tar -xf kasm_release_1.14.0.7f3582.tar.gz
    sudo bash kasm_release/install.sh --offline-workspaces /tmp/kasm_release_workspace_images_arm64_1.14.0.7f3582.tar.gz --offline-service /tmp/kasm_release_service_images_arm64_1.14.0.7f3582.tar.gz

[SRC](https://kasmweb.com/docs/latest/index.html)
