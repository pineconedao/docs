# Lucky Treasure Box Lottery Event

The PineconeDAO platform has launched a lottery event called the **Lucky Treasure Box**. The Lucky Treasure Box is a smart contract, and users must place their Mysterious Keys into the treasure box in order to participate in each round of the lottery event. Each Mysterious Key has a lucky number, and the larger the number, the higher the chances of winning.

When the Lucky Treasure Box prize pool conditions are met, and the number of participating Mysterious Keys reaches 1,000, the lottery event begins. Taking an event with a prize pool of 2,000 USDT as an example. To ensure the fairness and randomness of the lottery results, the PineconeDAO platform uses a verifiable random number provided by the third-party, **Chainlink**.

<figure><img src="https://4279269193-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F1qGfmU9m15rnNXyUpRaF%2Fuploads%2FaG0MnTKnqTRBSN5KCTvS%2Fluckybox.png_400.png?alt=media&#x26;token=aadcf3ee-9e3d-4786-a1c9-0be5d696ffa4" alt=""><figcaption></figcaption></figure>

When the **Chainlink random number** is generated, two numbers are produced. The first number is used to determine the winning Mysterious Key's number, and the second number is compared with the Mysterious Key's lucky number. For example, when you participate with a Mysterious Key, it will generate a number (e.g., 80) upon joining the event, while the Mysterious Key's lucky number is 10. When the two random numbers generated are 80 and 5, it means that the Mysterious Key with the number 80 has won. If the random numbers generated are 80 and 12, the Mysterious Key with number 80 does not win, and the system will continue to search for the Mysterious Key with number 81. If its lucky number is less than 11, the search continues for the Mysterious Key with number 82, and so on, until a Mysterious Key meeting the conditions wins.

{% hint style="info" %}
This **winning logic** is straightforward, and compared to traditional winning formulas, it has a very high winning rate and guarantees that a user wins in each round. Through this event, the **PineconeDAO platform provides users with more wealth growth opportunities**, while also enhancing community activity and cohesion.
{% endhint %}

Here are two examples of different Mysterious Key NFTs winning results under the same random number:

**Example 1**: Suppose you hold an **Iron Mysterious Key NFT**, with number 50 and lucky number 1. When the Chainlink-generated random number is 50 and 2, your Iron Mysterious Key NFT lucky number 1 < 2, indicating no win.

**Example 2**: Suppose you hold a **Gold Mysterious Key NFT**, with number 50 and lucky number 8. When the Chainlink-generated random number is 50 and 2, your Gold Mysterious Key NFT lucky number 8 >= 2, indicating a win. However, since the Gold Mysterious Key NFT's lucky number is 8, much higher than the Iron Mysterious Key NFT's lucky number 1, the Gold Mysterious Key NFT has a higher probability of winning under the same random number.

{% hint style="info" %}
**Winning Formula**: The first random number must be equal to the Mysterious Key NFT's number when joining the event, and the second random number must be less than or equal to the Mysterious Key NFT's lucky number.
{% endhint %}

Through these two examples, it is clear that **different levels of Mysterious Key NFTs will produce entirely different winning results** under the same random number. Gold Mysterious Key NFTs have higher lucky numbers, so they have a higher chance of winning in the lottery event. This encourages users to actively participate in the event and strive to upgrade their Mysterious Key NFTs to increase their chances of winning.

In conclusion, the **PineconeDAO platform, through the Lucky Treasure Box event, provides users with more wealth growth opportunities and enhances community activity and cohesion**. This innovative design allows users to enjoy richer entertainment elements during the investment process, thereby improving user engagement and platform loyalty.
