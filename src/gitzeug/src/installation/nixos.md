## Nixos
1. Add this GitHub repository to the inputs of your flake.nix:
   ```nix
   gitzeug.url = "github:thaemisch/gitzeug";
   ```
2. Add the package to your configuration.nix:
   ```nix
   environment.systemPackages = with pkgs; [
      ...
      inputs.gitzeug.packages.${pkgs.system}.gitzeug
   ];
   ```

   At some later point, I also plan to publish the package on nixpkgs.
