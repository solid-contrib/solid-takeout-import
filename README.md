# solid-takeout-import
Import your Google Takeout (etc) data into your solid pod so you can keep it and use it with Solid apps

Google allows you to take the data you have on Google Plus and similar things
end export it at the [Google Takeout website](https://takeout.google.com/).  

You select various sorts of data, then ask for it to be delivered in `.zip` file fomat or `.tgz` format.  Google then
does it in the background, then sends you an email with a link to the archive when it is ready to download.
(You can also ask for it to be stored in various places you control, but not *yet* solid pods,)

- You click on the download link on your computer, and get a zip file (or a .tgz file)

The goal of this project is to take the file you downloaded and convert it into
an interoperable form for solid apps you may want to use.

What you can do on your computer of course is:

- Double clicked on the zip file to unwrap the files onto your computer's file system.
- Explore the files on your computer.

The goal is to be able in future to

- Upload the Zip file onto your solid pod by dragging it onto a folder's green '+' icon
- Run this code to to find your own existing solid assets such as contacts and photos
- Use it to copy from your takeout archive file into your contacts without replication.
- Ideally, if you have already imported the data that copy will be eft, and just new stuff added.

Things which we are looking for:

- A complete *spec* of Google Takeout, etc  (A LDP graph shape would be ideal)
- The best vcard parser to use
- The best JS ical parser to use


This as an MIT licensed open source project... contributions are very welcome!  
including taking over the whole project.

timbl



##See also:

### Amazon
- Marc Salzman [Amazon (and Alexa) know a whole lot about you. Here's how download and delete that info](https://www.usatoday.com/story/tech/columnist/saltzman/2018/04/04/amazon-and-alexa-know-whole-lot-you-heres-how-download-and-delete-info/482286002/)
- [Create an Order History Report(https://www.amazon.com/gp/help/customer/display.html?nodeId=200131240)

### Apple
- Tidbits, [How to Download all Your Apple Data](https://tidbits.com/2018/05/31/how-to-download-all-your-apple-data/)
- privacy.apple.com

### Facebook
- [What to look for in yoruu Facebook data - and how to find it](https://www.wired.com/story/download-facebook-data-how-to-read/)
- [Facebook Download your data](https://www.facebook.com/dyi/)

### Google

- [Google Takeout](https://takeout.google.com/)

### Microsoft

- Todd Haselton, [How to download a copy of everything Microsoft knows about you](https://www.cnbc.com/2018/04/18/how-to-download-a-copy-of-everything-microsoft-knows-about-me.html)

### Twitter
- [How to download your Twitter archive](https://help.twitter.com/en/managing-your-account/how-to-download-your-twitter-archive)
- https://twitter.com/settings/account
- https://twitter.com/settings/your_twitter_data
