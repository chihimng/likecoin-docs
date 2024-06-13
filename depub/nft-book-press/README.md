---
description: Publish NFT eBook with LikeCoin NFT Book Press
---

# Publish NFT eBook

{% hint style="info" %}
Publish NFT requires the [Keplr Browser Extension](../../general-guides/wallet/keplr/) and [LikeCoin](https://like.co/) on a desktop computer
{% endhint %}

Publishing an NFT eBook on the blockchain involves the following processes:

1. [Prepare the ePub File](./#create-an-epub-file-and-enter-metadata)
2. [Register ISCN](./#register-iscn)
3. [List the Book for Sale](./#list-the-book-for-sale)

***

## Create an epub file and enter metadata

Create an [ePub](https://en.wikipedia.org/wiki/EPUB) file and enter [metadata](../what-is-iscn/). First, create the ePub file for the eBook, and ensure that the metadata has been entered and organized. Metadata includes book title, author, cover image, publication date, description, etc. Taking the commonly used ePub editing software as an example:

#### calibre

In [calibre](https://calibre-ebook.com/), the "Edit Metadata" button is in the upper left corner of the screen. After organizing the metadata, click "Save to disk".

<figure><img src="../../.gitbook/assets/NFT Book Press 1.png" alt=""><figcaption><p>The "Edit Metadata" and "Save to disk" buttons in calibre</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/NFT Book Press 2.png" alt=""><figcaption><p>Click "OK" after edited metadata</p></figcaption></figure>

#### Sigil

In [Sigil](https://sigil-ebook.com/), you can press the F8 key to edit metadata on the fly.

<figure><img src="../../.gitbook/assets/NFT Book Press 3.png" alt=""><figcaption><p>In Sigil press the F8 key to edit metadata</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/NFT Book Press 4.png" alt=""><figcaption><p>Click "OK" after edited metadata</p></figcaption></figure>

***

## Register ISCN

After preparing the ePub file, register it as an ISCN.

### Step 1: Upload the file

Visit the[ app.like.co](https://app.like.co/) website and click "Register ISCN".

<figure><img src="../../.gitbook/assets/NFT Book Press 5.png" alt=""><figcaption><p>Visit the app.like.co website and click "Register ISCN"</p></figcaption></figure>

A pop-up window will appear; click on Keplr to connect the wallet.

<figure><img src="../../.gitbook/assets/NFT Book Press 6.png" alt=""><figcaption><p>A pop-up window will appear; click on Keplr to connect the wallet</p></figcaption></figure>

Click "Select a file" to upload the prepared ePub file.

<figure><img src="../../.gitbook/assets/NFT Book Press 7.png" alt=""><figcaption><p>Click "Select a file" to upload the prepared ePub file</p></figcaption></figure>

The system will automatically split the ePub file content into two files: one is the ePub file, and the other is the book cover image file. Check if everything is okay, then click "Start Upload". The system will upload these two files to the distributed network.

<figure><img src="../../.gitbook/assets/NFT Book Press 8.png" alt=""><figcaption><p>Click "Start Upload" to upload the two files to the distributed network</p></figcaption></figure>

The Keplr wallet will pop up a window several times; click "Approve" to sign and wait for a while.

<figure><img src="../../.gitbook/assets/NFT Book Press 9.png" alt=""><figcaption><p>Click "Approve" on Keplr to sign</p></figcaption></figure>

### Step 2: Enter book information

"File Ready" appears, indicating that the file has been successfully uploaded. The system will automatically fill in the information based on the metadata content. The user can change them if they want:

<figure><img src="../../.gitbook/assets/NFT Book Press 10.png" alt=""><figcaption><p>"File Ready" appears</p></figcaption></figure>

1. Type: The default is "Book" for NFT eBooks.
2. ISCN Title: The title of the book associated with the ISCN.
3. Description: A brief description of the NFT eBook.
4. Author: The author's name.
5. Stakeholders: The system will automatically add the author and the ISCN registrant as stakeholders.
6. Tags: These are used for classification purposes.
7. Downloadable URL: The file's name of the ePub when it is being downloaded.
8. URL: The URL of the ePub.
9. License: The default is "Copyright. All rights reserved" for copyright declaration.
10. Content Fingerprints: These are URL hashes of the book and its cover. Each pair corresponds to one file, including IPFS and AR (Arweave) formats. Click on the URLs to check whether the content has been successfully uploaded. For instance, the four hashes in the attached screenshot represent the IPFS ePub file, IPFS book cover file, AR ePub file, and AR book cover file.
11. \+Other settings: Click on it to fill in the URL and ISBN fields if required.

After confirming that everything is correct, click "Register".



<figure><img src="../../.gitbook/assets/NFT Book Press 11.png" alt=""><figcaption><p>Click "Register"</p></figcaption></figure>

The Keplr wallet will pop up a window several times; click "Approve" to sign. Be careful not to click "Retry"; just wait for a while.

<figure><img src="../../.gitbook/assets/NFT Book Press 14.png" alt=""><figcaption><p>Click "Approve" on Keplr to sign</p></figcaption></figure>

### Step 3: ISCN registration completed

The message "Completed! Here is your ISCN" appears, indicating that the ISCN has been successfully registered. The string of characters in the ISCN ID field will be used when listing the NFT eBook for sale; click to copy it. Note that the '/1' in the picture is the ISCN version number, which is not essential when creating NFT eBooks.

<figure><img src="../../.gitbook/assets/NFT Book Press 15.png" alt=""><figcaption><p>Completed ISCN registration and copy the ISCN ID</p></figcaption></figure>

***

## List the Book for Sale

Listing for sale is divided into two steps: minting the NFT eBook and listing it. An analogy to traditional publishing is printing manuscripts into books and placing them on bookshelves for sale.

### Step 1: Mint the NFT eBook

Visit the [LikeCoin NFT Book Press](https://likecoin.github.io/nft-book-press/) website, click "Mint NFT", enter the website, and click the "Connect Wallet" link in the upper right corner to connect with Keplr.

<figure><img src="../../.gitbook/assets/NFT Book Press 16.png" alt=""><figcaption><p>Visit the LikeCoin NFT BookPress website, click "Mint NFT"</p></figcaption></figure>

In the "Enter ISCN ID or NFT Class ID" field, input the ISCN ID previously registered on app.like.co, and please note that there is no need to include the ISCN version number. Afterward, click "Submit".

<figure><img src="../../.gitbook/assets/NFT Book Press 17.png" alt=""><figcaption><p>In the "Enter ISCN ID or NFT Class ID" field, enter the ISCN ID</p></figcaption></figure>

{% hint style="info" %}
If you forget your ISCN ID, you can retrieve it in "[My Works](https://app.like.co/works)" at app.like.co.&#x20;
{% endhint %}

The system will automatically extract the basic information of ISCN for you. Fill in other information required in the "By filling required information" tab.

* Enter the number of NFTs to mint in the "Number of NFT to mint" field.
* If your book file is in ePub format, the system will automatically extract the link to the AR cover and place it in the "Image URL" column.
* "External URL (optional)", "URI (optional)", and "Max number of supply for this NFT Class (optional)" can be filled in as needed.

After filling in and confirming that everything is correct, click "Mint". The Keplr wallet will pop up windows several times. Click "Approve" to sign.

<figure><img src="../../.gitbook/assets/NFT Book Press 18.png" alt=""><figcaption><p>Enter all the information and click "Mint"</p></figcaption></figure>

The 🎉 Success! screen appears, indicating that the NFT has been successfully minted. Click "Continue to publish NFT Book" to complete the listing. Click "View your NFT" to view minted NFT eBooks in [Liker Land](https://liker.land/).

<figure><img src="../../.gitbook/assets/NFT Book Press 20.png" alt=""><figcaption><p>. Click "Continue to publish NFT Book" to complete the listing. Click "View your NFT" to view minted NFT eBooks in Liker Land</p></figcaption></figure>

Since it is not yet available for sale, you will see the words "Sold Out".

<figure><img src="../../.gitbook/assets/NFT Book Press 21.png" alt=""><figcaption><p>Since it is not yet available for sale, you will see the words "Sold Out"</p></figcaption></figure>

### Step 2: Book Listing

Return to LikeCoin NFT BookPress, click "Continue to publish NFT Book", and the NFT Book Store Management Page will appear.

{% hint style="info" %}
If you accidentally closed the page, you can enter your NFT Class ID in [Step 1](./#register-iscn) "Enter ISCN ID or NFT Class ID", and you will see "Continue to publish NFT Book". The Class ID is the string after the URL of your NFT eBook. For example, your NFT URL is  https://liker.land/zh-Hant/nft/class/likenft1qq06n42guzvt087wxunaajvz3alx6wadq6mfz0yz57gffwsrgrasl2m59x, and the NFT Class ID is likenft1qq06n42guzvt087wxunaajvz3alx6wadq6mf z0yz57gffwsrgrasl2m59x.
{% endhint %}

The NFT Class ID of the minted NFT eBook appears in the New NFT Book Listing

<figure><img src="../../.gitbook/assets/NFT Book Press 22.png" alt=""><figcaption><p>The NFT Class ID of the minted NFT eBook appears in the New NFT Book Listing</p></figcaption></figure>

#### Pricing and Availability

* Unit Price in USD (Minimum 0.99 or 0 for free) - The minimum price is 0.9 US dollars, or enter 0 to give it away for free.
* Total number of NFT ebook/edition for sale - Fill in the sales quantity of this version of the NFT eBook. Suppose you minted 10 books, you can set 5 books as version one, and the other 5 books as version two, etc. Click "Add Edition" below to add multiple different versions. Note that the total number of NFT eBooks available for sale in each version cannot exceed the minted quantity.
* Delivery method of this book
  * Automatic deliver NFT - Automatically send the NFT eBook to the reader
  * Sign memo and manually deliver each NFT - Sign and manually send the NFT eBook to the reader
* Memo of this book - Automatically add a message to the reader when sending the NFT eBook
* Allow custom price - Readers can provide [extra tip](../nft-ebook/#step-2-show-your-support-with-a-tip) to the author when purchasing the NFT eBook.

<figure><img src="../../.gitbook/assets/NFT Book Press 23.png" alt=""><figcaption><p>Pricing and Availability</p></figcaption></figure>

#### Product Information

* Product name - You can set the version of the NFT eBook according to personal preference, such as Standard Edition, Free version, etc.
* Description (Optional) - You can enter a Chinese and English description of the NFT eBook version.

#### Shipping Options

Physical Goods - After selecting “Includes physical good that requires shipping,” it indicates that the book version is a physical copy, and readers will need to pay for shipping. Click “View Current Shipping Options” to see the currently available delivery methods.

<figure><img src="../../.gitbook/assets/NFT Book Press 23a.png" alt=""><figcaption><p>Product Information and Shipping Options</p></figcaption></figure>

**Shipping Options Info**

* Name of the shipping option - Fill in the name of the shipping method in both Chinese and English.
* Price(USD) of this shipping option - Specify the cost of this shipping method in US dollars.

Click “Set Shipping Options” to save this shipping method, and click “Add Options” to add more shipping methods. Once done, click “Save.”

<figure><img src="../../.gitbook/assets/NFT Book Press 23f.png" alt=""><figcaption><p>Shipping Options</p></figcaption></figure>

#### Connect to a Stripe Account

Click to start connecting to the Stripe account, see details:

{% content-ref url="stripe.md" %}
[stripe.md](stripe.md)
{% endcontent-ref %}

#### Email to receive sales notification

Enter the email address that needs to receive sales notifications, then click “Add”.

<figure><img src="../../.gitbook/assets/NFT Book Press 23b.png" alt=""><figcaption><p>Connect to a Stripe Account and Email to receive sales notification</p></figcaption></figure>

#### Advance Settings

Click on Advance Settings to enter additional content:

* Default Display Currency at Check out - Change the default US dollar display to Hong Kong dollars
* Shipping Options - Add shipping cost options
* Share sales data to wallets - Enter the wallet address that needs to receive sales data, then click “Add”
* Send NFT Grant - If you choose “Automatic deliver NFT,” Liker Land will automatically be granted with permission to send the NFT eBook to you.
* DRM Options
  * Force NFT claim before view - Selecting Must claim NFT to view means that readers must claim the NFT eBook to read
  * Insert cutomized message page in eBook - Automatically insert  custom message into NFT eBooks.
  * Disable File Download - Selecting Disable Download means not allowing readers to download the NFT eBook, only allowing online reading.
* Coupon Codes - Click "Add New" to set up various kind of coupons:
  * Coupon Code - Set the name of the coupon
  * Discount Multiplier - Range of Discount. For example, 10% is a 10% discount
  * Expiry Date - The end date of the offer
  * After setting up, click "Add" to add the coupon.
* Copy Purchase Link - Set up the purchase link
  * Price - Choose a version of the NFT eBook
  * Sales channel for this link - Enter a name, set up an exclusive purchase link for your sales channel to promote
  * Copy Purchase Link - Click "Copy Purchase Link" to copy the exclusive link for the sales channel
  * Purchase Link QR Code - Click "Download" to download the QR Code of the exclusive link

<figure><img src="../../.gitbook/assets/NFT Book Press 23c.png" alt=""><figcaption><p>Advance Settings</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/Manage NFT Books 6.png" alt=""><figcaption><p>Coupon Codes</p></figcaption></figure>

After completing the settings, click "Submit". If the user chooses Automatic deliver NFT, a prompt will appear stating that once you choose to automatically send the NFT eBook to the reader, it cannot be changed to manual delivery. After confirming that it is correct, click "OK".

<figure><img src="../../.gitbook/assets/NFT Book Press 23e.png" alt=""><figcaption><p>Click "OK"</p></figcaption></figure>

The version of the book will appear in "Current Listing".

<figure><img src="../../.gitbook/assets/NFT Book Press 24.png" alt=""><figcaption><p>The version of the book will appear in "Current Listing"</p></figcaption></figure>

Go back to Liker Land to check that the NFT eBook has been successfully listed for sale.

<figure><img src="../../.gitbook/assets/NFT Book Press 25.png" alt=""><figcaption><p>The NFT eBook has been successfully listed for sale</p></figcaption></figure>
