/*
Assessment Requirements
1. Create a variable that can hold a number of NFT's. What type of variable might this be?
2. Create an object inside your mintNFT function that will hold the metadata for your NFTs.
    The metadata values will be passed to the function as parameters. When the NFT is ready,
    you will store it in the variable you created in step 1
3. Your listNFTs() function will print all of your NFTs metadata to the console (i.e. console.log("Name: " + someNFT.name))
4. For good measure, getTotalSupply() should return the number of NFT's you have created
*/

// create a variable to hold your NFT's
var my_nft = [];

// this function will take in some values as parameters, create an
// NFT object using the parameters passed to it for its metadata,
// and store it in the variable above.
function mintNFT (creator, type, price) 
{
    var NFTdetails = {NFTcreator: creator, NFTtype: type, NFTprice: price};
    my_nft.push(NFTdetails);
}

// create a "loop" that will go through an "array" of NFT's
// and print their metadata with console.log()
function listNFTs ()
{
    for (let index = 0; index < my_nft.length; index++)
    {
        console.log("NFT ID : \t\t" + (index+1));
        console.log("NFT Creator: \t" + my_nft[index].NFTcreator);
        console.log("NFT Type: \t\t" + my_nft[index].NFTtype);
        console.log("NFT Price: \t\t" + my_nft[index].NFTprice + "\n");
    }
}

// print the total number of NFTs we have minted to the console
function getTotalSupply()
{
    console.log("\nTotal NFT's minted: " + my_nft.length);
}

// call your functions below this line
mintNFT("Daksh", "Gaming", 80000);
mintNFT("Vansh", "Music", 126000);
listNFTs();
getTotalSupply();
