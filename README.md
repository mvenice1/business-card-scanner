# Business Card Scanner Add-on

Welcome and thank you for installing the Business Card Scanner Add-on! This tool makes it easy to convert business cards into contacts on your Google Account.

This project is currently in the testing phase. If you're interested in becoming a tester, feel free to reach out!

## 🚀 Getting Started

### 1. Launch the Add-on

You can open the Business Card Scanner in two ways:

- **From Gmail**  
  Open Gmail and look for the **Business Card Scanner** icon in the right-hand sidebar. Click it to launch the add-on.

- **Using a Direct Link**  
  [Click here to open the scanner]([https://script.google.com/macros/s/XXXXXXXXXXXX/exec](https://script.google.com/macros/s/AKfycbyngrLu76m1EXUUjmzUHxtSZg0CSQymx8FmiayGYMRLWmmy0euxRe7iien7y7nzsRjthg/exec))  
  _Replace the URL above with your deployed Web App URL._

  > 💡 **Pro Tip:** For quick access on your phone, create a home screen shortcut:  
  > - **iPhone**: Open the link in Safari, tap the **Share** icon, and select **"Add to Home Screen."**  
  > - **Android**: Open the link in Chrome, tap the **three-dot menu**, and choose **"Add to Home screen."**

---

### 2. Authorize Access

The first time you launch the add-on, you’ll be prompted to grant **Google account permissions**.

This authorization allows the add-on to:

- Upload and scan images to extract contact details
- Autofill and submit contact information through the in-app form
- Create new contacts in your Google Contacts

> 🔒 **Privacy Note:**  
> The only action this app performs on your Google Account is the creation of a contact using the  
> `People.People.createContact(resource)` method from the **Google People API**.  
> External access is required solely to process the scanned image and structure the data into contact fields.  
> No information is shared outside your Google environment

---

### 3. Scan a Business Card

1. Click the **"Take or Upload a Business Card"** button.
2. Capture or select an image of the business card.
3. The add-on will:
   - Process the image using OCR
   - Extract contact details
   - Display an editable form directly within the app
4. Review and submit the form to save the contact to your Google Contacts.

> 💡 **Pro Tip:** Using a computer? You can scan email signatures too!  
> Use the **Snipping Tool** (Windows) or **Screenshot** shortcut (Mac) to capture contact information from an email signature, then upload the image to process it just like a business card.

---

### 4. Continue Scanning

You can scan additional cards anytime — just click the **"Scan Another Card"** button to reset the interface and start a new scan.


Happy scanning!
