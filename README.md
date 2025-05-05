# Car-Rental-Platform

![screenshot(33)](https://github.com/user-attachments/assets/7f074b91-ca45-4b62-bd18-e5eab1f45d58)


# P2P Car Rental Platform

## 🚗 Project Title
P2P Car Rental Platform

## 📖 Project Description
A decentralized peer-to-peer (P2P) car rental marketplace built on Soroban smart contracts, enabling users to register, rent, and return cars without intermediaries.

## 🌍 Project Vision
To simplify and decentralize the car rental experience by giving car owners and renters direct access to each other via blockchain-powered contracts. This reduces cost, increases transparency, and enhances trust.

## ✨ Key Features
- **Register Cars:** Owners can list cars with pricing and model info.
- **Rent Cars:** Users can securely rent available cars.
- **Return Cars:** Renters can mark cars as returned.
- **Transparent Status:** Easily query car rental state and ownership.

## 📜 Contract Details

### Contract Address: CCDC6SYAHEPIGWVLWY3YW2VSDMHU6IGEW7MFFLFPUJVKHQZSC222JX3I

| Function         | Description                                      |
|------------------|--------------------------------------------------|
| `register_car`   | Register a new car with model and daily rate.    |
| `rent_car`       | Rent an available car.                           |
| `return_car`     | Mark the car as returned after usage.            |
| `get_car`        | Fetch details of a car by its ID.                |

### Contract Types

- **Car**: Holds metadata such as owner, model, price, and status.
- **RentalStatus**: Tracks if a car is available, rented, or returned.
- **CarKey**: Used to store and retrieve cars from the instance storage.

---

🛠 Built using [Soroban SDK](https://soroban.stellar.org/docs) for smart contract development on Stellar.
