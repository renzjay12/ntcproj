const mintedNFTs = [];


function mintNFT(name, description, image) {
  mintedNFTs.push({ name, description, image });
}


function listNFTs() {
  if (!mintedNFTs.length) {
    console.log("No NFTs minted yet!");
    return;
  }

  mintedNFTs.forEach(nft => {
    console.log("Name:", nft.name);
    console.log("Description:", nft.description);
    console.log("Image:", nft.image);
  });
}


const getTotalSupply = () => mintedNFTs.length;


mintNFT("Dog",
        "Dognft",
        "dog.jpg");
mintNFT("Rabbit",
        "Rabbitnft",
        "rabbit.jpg");
mintNFT("Frog",
        "Frognft",
        "frog.jpg");


listNFTs();


const totalNFTs = getTotalSupply();
console.log("Total NFTs minted:", totalNFTs);
