# Super Mario Drone :mushroom: :star:
  
  You should import it in the Cargo.toml as follow:  

  ```toml
  [dependencies]
  ap2024_rustinpeace_supermariodrone = { git = "https://github.com/Rust-In-Peace-AP/Super-Mario-Drone.git" }
  ```

  Then in the code like this: :coin: :coin:

  ```rust
  use ap2024_rustinpeace_supermariodrone;
  ...
  
  fn main(){
  
    let drone = ap2024_rustinpeace_supermariodrone::SuperMarioDrone::new(...);
  
  }
  
  
