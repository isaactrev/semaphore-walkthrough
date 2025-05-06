
# Semaphore Walkthrough
## 🎥 Project Demo

[![Watch the video](https://img.youtube.com/vi/x9byd2CVZ-U/0.jpg)](https://youtu.be/x9byd2CVZ-U)

# A Beginner’s Walkthrough of Semaphore

This project is a simplified walkthrough of how [Semaphore](https://semaphore.pse.dev/) works — a zero-knowledge protocol that enables anonymous signaling, voting, and feedback within a verified group. The goal is to demystify the core steps by walking through a functional example built on top of Semaphore’s official boilerplate.

## 🔍 Project Overview

Semaphore enables anonymous group membership and private signaling using zero-knowledge proofs. This project walks through:

1. **Identity Creation**  
   Users create a zk identity locally in their browser (trapdoor, nullifier, commitment).

2. **Group Membership**  
   Commitments are added to a Merkle tree, forming a privacy-preserving group.

3. **Feedback & Voting**  
   Users anonymously prove membership and submit a signal (feedback or vote) without revealing their identity.

## 🎥 Project Demo

[![Watch the video](https://img.youtube.com/vi/x9byd2CVZ-U/0.jpg)](https://youtu.be/x9byd2CVZ-U)

This short 5-minute video walks through the three main UI screens (Identity, Group, Feedback) and explains how the Semaphore protocol works under the hood.

## 🛠 Technologies Used

- [Next.js App Router (13+)](https://nextjs.org/docs)
- [Hardhat](https://hardhat.org/)
- [Semaphore Protocol](https://semaphore.pse.dev/)
- [Chakra UI](https://chakra-ui.com/)
- TypeScript

## 🧪 Local Setup

Clone this project and install dependencies:

```bash
git clone https://github.com/YOUR_USERNAME/semaphore-walkthrough.git
cd semaphore-walkthrough
yarn install
yarn dev
