# Instructions for adding Addressfinder to Gravity Forms.

Addressfinder provides an address autocomplete service which enables customers to search and select verified Australian and New Zealand addresses. 

### Step 1
Select 'Forms' in the Wordpress sidebar and create a new form. If you have an existing form you want to add Addressfinder to, skip to Step x.

![image](https://user-images.githubusercontent.com/23350144/68250392-b412c200-0085-11ea-93d6-210fe7a9d610.png)

### Step 2
In the form editor, drag the 'Single Line Text' option into your form.

![image](https://user-images.githubusercontent.com/23350144/68250477-e02e4300-0085-11ea-97a3-5d720041a980.png)

### Step 3
Update this form field information by clicking on the Single Line Text field, then change the ‘Field Label’ to *Address*, *Residential Address* or *Postal Address*. You may also want to update the placeholder text by clicking 'Appearance' and updating the text in the 'placeholder' field. Adding *Just start typing...* can be a good idea.

![image](https://user-images.githubusercontent.com/23350144/68250559-05bb4c80-0086-11ea-9cc8-3e20d914f49a.png)

### Step 4
Add an HTML element by dragging an ‘HTML’ option from the Standard Fields section into the form and drop it underneath your address field.

![image](https://user-images.githubusercontent.com/23350144/68250623-27b4cf00-0086-11ea-98bf-5250bae6b1cf.png)

### Step 5
Expand the HTML element by clicking on it then paste the code from below into the 'Content' section of this 'General' tab. The code to be pasted into this area can be copied from any of the Code Options links below according to your needs.

![image](https://user-images.githubusercontent.com/23350144/68250686-4915bb00-0086-11ea-89db-3ee09ff284f2.png)

### Code Options:
- [Australian Postal Addresses (includes PO Box addresses](https://github.com/abletech/addressfinder-gravity-forms/blob/master/au-postal-with-po-boxes)
- [Australian Postal Addresses (excludes PO Box addresses)](https://github.com/abletech/addressfinder-gravity-forms/blob/master/au-postal-without-po-boxes)
- [Australian Physical Addresses](https://github.com/abletech/addressfinder-gravity-forms/blob/master/au-physical-addresses)
- [New Zealand Postal Addresses (includes PO Box addresses)](https://github.com/abletech/addressfinder-gravity-forms/blob/master/nz-postal-with-po-boxes)
- [New Zealand Postal Addresses (excludes PO Box addresses)](https://github.com/abletech/addressfinder-gravity-forms/blob/master/nz-postal-without-po-boxes)
- [New Zealand Physical Addresses](https://github.com/abletech/addressfinder-gravity-forms/blob/master/nz-physical-addresses)

### Step 6
Make adjustments to the code you have just pasted into the HTML so that it is connects to your form and Addressfinder account. You will need to repace the 'ADDRESS_ID_HERE' ID with your address field's ID and 'ADDRESSFINDER_DEMO_KEY' with your Addressfinder account KEY.

### Step 7
Save then test the page.
