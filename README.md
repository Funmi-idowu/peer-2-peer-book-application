# Book Review Application
## By Funmi Idowu

## Project Proposal

In an era where literature thrives and readers seek insights into their next captivating read, centralized platforms often dictate the discourse around books, limiting diverse perspectives and impeding organic interactions. Our proposal is to develop a decentralized peer-to-peer (P2P) book review application, empowering readers to share, discover, and discuss books freely.

### Application Overview:

This application will provide a platform for readers to create book reviews, publish book reviews, list books of interest, list other peers we discovered on the network, list published book reviews of a given peer and list all book reviews of all peers we know

### Key Features:

Decentralized Reviews: Readers can post reviews and ratings for books without reliance on central servers, ensuring diverse perspectives and uncensored opinions.
Peer Discovery: Users can connect with fellow readers through decentralized mechanisms, facilitating organic interactions and diverse literary discussions.
Secure Communication: Encrypted communication ensures privacy and integrity in discussions, fostering trust among users.

### Utilizing P2P Network:

The P2P network forms the backbone of our book review application, enabling decentralized storage and communication.

- Distribution: Reviews are distributed across multiple network nodes, ensuring redundancy and availability.
- Peer Discovery: Peers announce their presence within the network, facilitating organic connections and fostering a vibrant community of readers.

This decentralized peer-to-peer book review application empowers readers to engage in open, diverse discussions about literature, free from the constraints of centralized platforms. By leveraging a P2P network, the exchange of literary insights while preserving user privacy and fostering a dynamic community of readers is facilitated.

## Usage

1. Clone repo onto ypur device
2. Command to run program: RUST_LOG=info cargo run
3. Prompt Commands:
   - List peers: command will this the other users on the network
   - List reviews: this command will list all the book reviews within the book.json file
     - Format: list reviews
   - Create review: this command will allow users to create a book review
     - Format: create review title | genre | author | rating (ex: ⅗) | review
   - Publish review: this command will publish a users book review, in the books.json it will appear was public being true or false
     - Format: publish review (insert id number)
   - Delete review: this commands deletes a book review using the reviews id
     - Format: delete review (insert id number)
