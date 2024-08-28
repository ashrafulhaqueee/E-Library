# E-Library Dapp

![image](https://github.com/user-attachments/assets/0dd07dfb-98da-45ce-89b5-85a24d78966c)


## Vision

The **eLibrary DApp** aims to revolutionize the traditional library system by leveraging blockchain technology. Our decentralized library system provides a transparent, secure, and immutable way to manage, borrow, and return books. By eliminating the need for intermediaries, we empower users to directly interact with the library, ensuring a seamless and trustless experience.

## Flowchart

```plaintext
+-----------------+       +-----------------+
|                 |       |                 |
|  Add New Book   |-----> |                 |
|  (Owner Only)   |       |   Borrow Book   |
|                 |       |                 |
+-----------------+       |   (User)        |
                           +-----------------+
                                 |
                                 v
                           +-----------------+
                           |                 |
                           |  Return Book    |
                           |   (User)        |
                           +-----------------+

```

1. **Add New Book**: The contract owner can add new books to the library.
2. **Borrow Book**: Users can borrow available books from the library.
3. **Return Book**: Users can return borrowed books to the library.

## Smart Contract

### Contract Address

- **Ethereum Mainnet**: `0xf8e81D47203A594245E36C48e151709F0C19fBe8`


### How to Interact

1. **Add Book**: Only the contract owner can add a book using the `addBook(string memory title, string memory author)` function.
2. **Borrow Book**: Any user can borrow an available book using the `borrowBook(uint256 bookId)` function.
3. **Return Book**: The borrower can return the book using the `returnBook(uint256 bookId)` function.
4. **Get Book Details**: Anyone can view a book’s details using the `getBook(uint256 bookId)` function.

## Future Scope

- **Decentralized Governance**: Implement a decentralized governance model where users can vote on library management decisions.
- **Tokenization**: Introduce a token system to incentivize book sharing and other contributions.
- **Book Reviews & Ratings**: Enable users to review and rate books, providing feedback to other users.
- **Interoperability**: Integrate with other decentralized applications (dApps) for broader utility and functionality.

## Contact

For any inquiries or contributions, please reach out:

- **Name**: Ashraful Haque
- **Email**: 786ashrafulhaque@gmail.com

---

This project is open-source and available under the MIT License. Contributions are welcome!

---

*Note: Please replace the placeholders with your actual details and the deployed contract address.*
