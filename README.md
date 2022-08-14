1/ installer rust
2/ installer la lib postgres dev
sudo apt install libpq-dev
3/ installer docker, et docker compose
4/ executer le docker compose de pg+pgAdmin, puis ajouter le serveur local (configurer le master password de pgAdmin, par ex. "pgadmin")
5/ utiliser une version nigthly de rust : 
https://stackoverflow.com/questions/66605551/build-fails-with-error-pear-requires-a-dev-or-nightly-version-of-rustc-even
6/ coder en se basant de l'article : 
https://genekuo.medium.com/creating-a-rest-api-in-rust-with-persistence-rust-rocket-and-diesel-a4117d400104

7/ écrire le main.rs pour appeler le routeur::create_routes
8/ execution avec cargo run, et fixer les erreurs (module rust)
https://github.com/genekuo/rust-microservices/blob/rocket-diesel/src/sample/handler.rs
9/ tester avec curl, et navigateur
cargo run
