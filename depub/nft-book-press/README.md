---
description: Publish eook with LikeCoin NFT Book Press
---

# Publish ebook

{% hint style="info" %}
Before publishing, you can refer to the [FAQ: Listing Liker Land ebooks](nft-book-press-faq.md)
{% endhint %}

{% hint style="info" %}
Publish NFT requires a desktop computer and [LikeCoin](https://like.co/) on a desktop computer
{% endhint %}

Publishing an ebook on the blockchain involves the following processes:

1. [Prepare the EPUB File](./#create-an-epub-file-and-enter-metadata)
2. [Register ISCN](./#register-iscn)
3. [List the Book for Sale](./#list-the-book-for-sale)

and other follow up actions:

4. [Manage NFT books](nft-book-store.md)
5. [Manage Book Collection](collection.md)
6. [NFT Book Press User Setting](manage-user-setting/)
7. [ebooks Replenishment](replenishment.md)
8. [Creator’s Introduction on Liker Land BookStore](./#creators-introduction)
9. [Transfer ebook or Batch send NFT to more than one wallet](./#transfer-nft-ebook-or-batch-send-nft-to-more-than-one-wallet)
10. [Import EPUB files to various ereaders](./#import-epub-files-to-various-ereaders)
11. [Modify ebook](modify-nft-ebook.md)
12. [Burn ebook](burn-nft-ebook.md)

***

## Create an EPUB file and enter metadata

Create an [EPUB](https://en.wikipedia.org/wiki/EPUB) file and enter [metadata](../what-is-iscn/). First, create the EPUB file for the eBook, and ensure that the metadata has been entered and organized. Metadata includes book title, author, cover image, publication date, description, etc. Taking the commonly used EPUB editing software as an example:

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

After preparing the EPUB file, register it as an ISCN.

### Step 1: Upload the file

Visit the[ app.like.co](https://app.like.co/) website and click "Register ISCN".

<figure><img src="../../.gitbook/assets/NFT Book Press 5.png" alt=""><figcaption><p>Visit the app.like.co website and click "Register ISCN"</p></figcaption></figure>

A pop-up window will appear to connect your wallet. It is recommended to register and **log in with a Liker ID using Email/Social**. For more details, refer to:

{% content-ref url="../../user-guide/liker-id/register/" %}
[register](../../user-guide/liker-id/register/)
{% endcontent-ref %}

<figure><img src="../../.gitbook/assets/NFT Book Press 6.png" alt=""><figcaption><p>A pop-up window will appear; click and connect to a wallet</p></figcaption></figure>

Click "Select a file" to upload the prepared EPUB file.

<figure><img src="../../.gitbook/assets/NFT Book Press 7.png" alt=""><figcaption><p>Click "Select a file" to upload the prepared EPUB file</p></figcaption></figure>

The system will automatically split the EPUB file content into two files: one is the EPUB file, and the other is the book cover image file. Check if everything is okay, then click "Start Upload". The system will upload these two files to the distributed network.

<figure><img src="../../.gitbook/assets/NFT Book Press 8.png" alt=""><figcaption><p>Click "Start Upload" to upload the two files to the distributed network</p></figcaption></figure>

### Step 2: Enter book information

"File Ready" appears, indicating that the file has been successfully uploaded. The system will automatically fill in the information based on the metadata content. The user can change them if they want:

<figure><img src="../../.gitbook/assets/NFT Book Press 10.png" alt=""><figcaption><p>"File Ready" appears</p></figcaption></figure>

1. Type: The default is "Book" for ebook.
2. ISCN Title: The title of the book associated with the ISCN.
3. Description: A brief description of the ebook.
4. Author: The author's name.
5. Stakeholders: The system will automatically add the author and the ISCN registrant as stakeholders.
6. Tags: These are used for classification purposes.
7. Downloadable URL: The file's name of the EPUB when it is being downloaded.
8. URL: The URL of the EPUB.
9. License: The default is "Copyright. All rights reserved" for copyright declaration.
10. Content Fingerprints: These are URL hashes of the book and its cover. Each pair corresponds to one file, including IPFS and AR (Arweave) formats. Click on the URLs to check whether the content has been successfully uploaded. For instance, the four hashes in the attached screenshot represent the IPFS EPUB file, IPFS book cover file, AR EPUB file, and AR book cover file.
11. \+Other settings: Click on it to fill in the URL and ISBN fields if required.

After confirming that everything is correct, click "Register".

<figure><img src="../../.gitbook/assets/NFT Book Press 11.png" alt=""><figcaption><p>Click "Register"</p></figcaption></figure>

### Step 3: ISCN registration completed

The message "Completed! Here is your ISCN" appears, indicating that the ISCN has been successfully registered. The string of characters in the ISCN ID field will be used when listing the ebook for sale. Note that the '/1' in the picture is the ISCN version number.

<figure><img src="../../.gitbook/assets/NFT Book Press 15.png" alt=""><figcaption><p>Completed ISCN registration and copy the ISCN ID</p></figcaption></figure>

***

## List the Book for Sale

Listing for sale is divided into two steps: minting the ebook and listing it. An analogy to traditional publishing is printing manuscripts into books and placing them on bookshelves for sale.

### Step 1: Mint the ebook

Click ‘Mint Book’ at the top right corner of the ISCN record.

<figure><img src="../../.gitbook/assets/NFT Book Press 9.png" alt=""><figcaption><p>Click "Mint Book"</p></figcaption></figure>

The system will automatically redirect to the [LikeCoin NFT Book Press](https://likecoin.github.io/nft-book-press/) website, and the ISCN ID will be pre-entered in the ‘Enter ISCN ID or NFT Class ID’ field. After clicking "Sign In" at the top right corner to log in to the website, click "Submit".

<figure><img src="../../.gitbook/assets/NFT Book Press 17.png" alt=""><figcaption><p>In the "Enter ISCN ID or NFT Class ID" field, enter the ISCN ID</p></figcaption></figure>

Alternatively, go directly to the [LikeCoin NFT Book Press](https://likecoin.github.io/nft-book-press/) website and click "Mint NFT". Click ‘Sign In’ at the top right corner to log in. Manually enter the previously registered ISCN ID in the "Enter ISCN ID or NFT Class ID" field and then click "Submit".

<figure><img src="../../.gitbook/assets/NFT Book Press 16.png" alt=""><figcaption><p>Visit the LikeCoin NFT BookPress website, click "Mint NFT"</p></figcaption></figure>

In the "Enter ISCN ID or NFT Class ID" field, input the ISCN ID previously registered on app.like.co, and please note that there is no need to include the ISCN version number. Afterward, click "Submit".

{% hint style="info" %}
If you forget your ISCN ID, you can retrieve it in "[My Works](https://app.like.co/works)" at app.like.co.&#x20;
{% endhint %}

The system will automatically extract the basic information of ISCN for you. Fill in other information required in the "By filling required information" tab.

* Enter the number of NFTs to mint in the "Number of NFT to mint" field.
* If your book file is in EPUB format, the system will automatically extract the link to the AR cover and place it in the "Image URL" column.
* "External URL (optional)", "URI (optional)", and "Max number of supply for this NFT Class (optional)" can be filled in as needed.

After filling in and confirming that everything is correct, click "Mint".

<figure><img src="../../.gitbook/assets/NFT Book Press 18.png" alt=""><figcaption><p>Enter all the information and click "Mint"</p></figcaption></figure>

The 🎉 Success! screen appears, indicating that the NFT has been successfully minted. Click "Continue to publish NFT Book" to complete the listing. Click "View your NFT" to view minted ebook in [Liker Land](https://liker.land/).

<figure><img src="../../.gitbook/assets/NFT Book Press 20.png" alt=""><figcaption><p>. Click "Continue to publish NFT Book" to complete the listing. Click "View your NFT" to view minted ebook in Liker Land</p></figcaption></figure>

Since it is not yet available for sale, you will see the words "Sold Out".

<figure><img src="../../.gitbook/assets/NFT Book Press 21.png" alt=""><figcaption><p>Since it is not yet available for sale, you will see the words "Sold Out"</p></figcaption></figure>

### Step 2: Book Listing

Return to LikeCoin NFT BookPress, click "Continue to publish NFT Book", and the NFT Book Store Management Page will appear.

{% hint style="info" %}
If you accidentally closed the page, you can enter your NFT Class ID in [Step 1](./#register-iscn) "Enter ISCN ID or NFT Class ID", and you will see "Continue to publish NFT Book". The Class ID is the string after the URL of your ebook. For example, your NFT URL is  https://liker.land/zh-Hant/nft/class/likenft1qq06n42guzvt087wxunaajvz3alx6wadq6mfz0yz57gffwsrgrasl2m59x, and the NFT Class ID is likenft1qq06n42guzvt087wxunaajvz3alx6wadq6mf z0yz57gffwsrgrasl2m59x.
{% endhint %}

The NFT Class ID of the minted ebook appears in the New NFT Book Listing

<figure><img src="../../.gitbook/assets/NFT Book Press 22.png" alt=""><figcaption><p>The NFT Class ID of the minted ebook appears in the New NFT Book Listing</p></figcaption></figure>

#### Pricing and Availability

* Unit Price in USD (Minimum 0.99 or 0 for free) - The minimum price is 0.9 US dollars, or enter 0 to give it away for free.
* Total number of NFT ebook/edition for sale - Fill in the sales quantity of this version of the ebook. Suppose you minted 10 books, you can set 5 books as version one, and the other 5 books as version two, etc. Click "Add Edition" below to add multiple different versions. Note that the total number of ebooks available for sale in each version cannot exceed the minted quantity.
* Delivery method of this book - You can choose between two different ways to send ebooks:
  1. Automatic deliver NFT - Automatically send the ebook to the reader. Once this option is set, it cannot be changed.
     * Memo of this book - If you choose to automatically send the ebook to the reader, a memo will be automatically added to the reader upon delivery.
  2. Sign memo and manually deliver each NFT - Sign and manually send the ebook to the reader
     * Is Physical only good - If you choose to sign manually, this option will pop up to ask if the book only contains a physical version, displaying "This edition does not contain digital file/NFT". If selected, it means this version does not provide an ebook file and the physical book will be sent by the author. Please add the postage option in Advanced Settings.
* Allow custom price - Readers can provide [extra tip](../nft-ebook/#step-2-show-your-support-with-a-tip) to the author when purchasing the ebook.

<figure><img src="../../.gitbook/assets/NFT Book Press 23.png" alt=""><figcaption><p>Pricing and Availability</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/NFT Book Press 24 (1).png" alt=""><figcaption><p>Sign memo and manually deliver each NFT</p></figcaption></figure>

#### Product Information

* Product name - You can set the version of the ebook according to personal preference, such as Standard Edition, Free version, etc.
* Description (Optional) - You can enter a Chinese and English description of the ebook version.

<figure><img src="../../.gitbook/assets/NFT Book Press 23a.png" alt=""><figcaption><p>Product Information</p></figcaption></figure>

#### Shipping Options

Physical Goods - After selecting “Includes physical good that requires shipping,” it indicates that the book version is a physical copy, and readers will need to pay for shipping. However, you need to configure the settings in Advanced Settings first before this option can be enabled.

<figure><img src="../../.gitbook/assets/NFT Book Press 26.png" alt=""><figcaption><p>Shipping Options</p></figcaption></figure>

#### Connect to a Stripe Account

Click to start connecting to the Stripe account, see details:

{% content-ref url="manage-user-setting/stripe.md" %}
[stripe.md](manage-user-setting/stripe.md)
{% endcontent-ref %}

<figure><img src="../../.gitbook/assets/NFT Book Press 27.png" alt=""><figcaption><p>Connect to a Stripe Account</p></figcaption></figure>

#### Email to receive sales notification

Enter the email address that needs to receive sales notifications, then click “Add”.

<figure><img src="../../.gitbook/assets/NFT Book Press 23b.png" alt=""><figcaption><p>Email to receive sales notification</p></figcaption></figure>

#### Advance Settings

Click Advanced Settings to configure the following additional options:

<figure><img src="../../.gitbook/assets/NFT Book Press 23c (1).png" alt=""><figcaption><p>Advance Settings</p></figcaption></figure>

#### Default Currency

Change the default US dollar display to Hong Kong dollars.

<figure><img src="../../.gitbook/assets/NFT Book Press 23d.png" alt=""><figcaption><p>Default Display</p></figcaption></figure>

**Shipping Options**

Shipping options, click the “+Add” in the top right corner.

<figure><img src="../../.gitbook/assets/NFT Book Press 23f.png" alt=""><figcaption><p>Click the “+Add” in the top right corner</p></figcaption></figure>

The “Editing Shipping Options” page appears.

* Name of the shipping option - Fill in the name of the shipping method in both Chinese and English.
* Price(USD) of this shipping option - Specify the cost of this shipping method in US dollars.
* Click “Add Options” to add more shipping methods.

Once done, click “Save" to save this shipping method.

<figure><img src="../../.gitbook/assets/NFT Book Press 23g.png" alt=""><figcaption><p>Editing Shipping Options</p></figcaption></figure>

#### Share sales data to wallets

Enter the wallet address that needs to receive sales data, then click “Add”. The Liker Land wallet address is added by default. Click “Grant” in the Send NFT Grant section to authorize this wallet to automatically send ebooks for you.

<figure><img src="../../.gitbook/assets/NFT Book Press 23h.png" alt=""><figcaption><p>Share sales data to wallets</p></figcaption></figure>

Click “Submit” on the Send NFT Authz Grants Management Page to authorize.

<figure><img src="../../.gitbook/assets/NFT Book Press 23i.png" alt=""><figcaption><p>Send NFT Authz Grants Management Page</p></figcaption></figure>

#### DRM Options

* Force NFT claim before view - Selecting Must claim NFT to view means that readers must claim the ebook to read
* Disable File Download - Selecting Disable Download means not allowing readers to download the ebook, only allowing online reading.
* Insert cutomized message page in eBook - Automatically insert a custom message page into the EPUB file.

<figure><img src="../../.gitbook/assets/NFT Book Press 23j.png" alt=""><figcaption><p>DRM Options</p></figcaption></figure>

After completing the settings, click "Submit". If the user chooses Automatic deliver NFT, a prompt will appear stating that once you choose to automatically send the ebook to the reader, it cannot be changed to manual delivery. After confirming that it is correct, click "OK".

<figure><img src="../../.gitbook/assets/NFT Book Press 23e.png" alt=""><figcaption><p>Click "OK"</p></figcaption></figure>

The version of the book will appear in "Current Listing".

<figure><img src="../../.gitbook/assets/NFT Book Press 24.png" alt=""><figcaption><p>The version of the book will appear in "Current Listing"</p></figcaption></figure>

Go back to Liker Land to check that the ebook has been successfully listed for sale.

<figure><img src="../../.gitbook/assets/NFT Book Press 25.png" alt=""><figcaption><p>The ebook has been successfully listed for sale</p></figcaption></figure>

***

You can continue to:

## Manage ebook

{% content-ref url="nft-book-store.md" %}
[nft-book-store.md](nft-book-store.md)
{% endcontent-ref %}

## Manage Book Collection

{% content-ref url="collection.md" %}
[collection.md](collection.md)
{% endcontent-ref %}

## Manage User Setting

{% content-ref url="manage-user-setting/" %}
[manage-user-setting](manage-user-setting/)
{% endcontent-ref %}

## Creator’s Introduction

Set your own introduction, profile picture, and display name so your supporters can know you better.&#x20;

{% content-ref url="../../user-guide/liker-id/edit-avatar-displayname.md" %}
[edit-avatar-displayname.md](../../user-guide/liker-id/edit-avatar-displayname.md)
{% endcontent-ref %}

## Transfer ebook or Batch send NFT to more than one wallet

Transfer or Gift ebook.

{% content-ref url="../transfer-writing-nft/" %}
[transfer-writing-nft](../transfer-writing-nft/)
{% endcontent-ref %}

{% content-ref url="nft-book-store.md" %}
[nft-book-store.md](nft-book-store.md)
{% endcontent-ref %}

### Import EPUB files to various ereaders

Besides using USB to import EPUB files to ereaders, different brands also support uploading via network interfaces:

* Kindle - [Send to Kindle](https://www.amazon.com/-/zh\_TW/gp/sendtokindle)
* Boox - [The Complete Guide of Transferring Files](https://shop.boox.com/blogs/news/the-complete-guide-of-transferring-files)
