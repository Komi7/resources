
|File name|Line No|Description|extra|
| ------ | ----------- |-------|----|
|configuration.nix|89|users.users.(your_username)|description = "you can change";|
|flake.nix|23|(your_username) = lib.nixosSystem|
|flake.nix|30|home-manager.users.(your_username)|
|home.nix|6|home.username = "your_username"; |
|home.nix|7|home.homeDirectory = "/home/your_username";|
