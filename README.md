# ZoKrates
## ZoKrates - Scalable Privacy-Preserving Off-Chain Computations

## Steps to execute :

* `root.zok` contains a basic code to prove root of 2 numbers.
# Compile
`zokrates compile -i root.zok`
<img width="985" alt="Screenshot 2024-02-06 at 9 19 13 AM" src="https://github.com/pranshurastogi/zoKrates/assets/12568291/18f46dde-734c-4211-99ac-202cf6d5e146">
# Perform the setup phase
`zokrates setup`
<img width="985" alt="Screenshot 2024-02-06 at 9 20 02 AM" src="https://github.com/pranshurastogi/zoKrates/assets/12568291/8db962bb-0578-4e3f-9d7f-2bc2574cc97b">
![image](https://github.com/pranshurastogi/zoKrates/assets/12568291/b67d6330-17f5-4faa-9a78-9a552a3b5523)
# Execute the program
`zokrates compute-witness -a 337 113569`
<img width="1077" alt="Screenshot 2024-02-06 at 9 20 48 AM" src="https://github.com/pranshurastogi/zoKrates/assets/12568291/e172326b-011d-4c22-b4cc-e215faf21888">

# Generate a proof of computation
`zokrates generate-proof`
<img width="1144" alt="Screenshot 2024-02-06 at 9 21 22 AM" src="https://github.com/pranshurastogi/zoKrates/assets/12568291/76b9cf79-a418-48cb-acd6-4f3bb1aac3ab">

# Export a solidity verifier
`zokrates export-verifier`
<img width="1225" alt="Screenshot 2024-02-06 at 9 21 46 AM" src="https://github.com/pranshurastogi/zoKrates/assets/12568291/86c8ac19-32a5-4da7-a4ee-a9f999d15e71">

# Verify natively
`zokrates verify`
<img width="1225" alt="Screenshot 2024-02-06 at 9 22 15 AM" src="https://github.com/pranshurastogi/zoKrates/assets/12568291/8d2748e4-ef59-488a-8d1e-2c0809cca43c">
