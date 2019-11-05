# Instructions for adding AddressFinder functionality to Gravity Forms.

AddressFinder provides an address autocomplete service which enables customers to search and select verified Australian and New Zealand addresses. 

### Step 1
Select 'Forms' in the Wordpress sidebar and create a new form. If you have an existing form you want to add AddressFinder to, skip to Step x.

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
Expand this HTML element by clicking on it. Then paste the code from below into the 'Content' section of this 'General' tab. Look through the address related options below to determine which code needs to be added to your page.

![image](https://user-images.githubusercontent.com/23350144/68250686-4915bb00-0086-11ea-89db-3ee09ff284f2.png)

### Step 6
Make adjustments to the code you have added so that it is connects to your form. You will need to update the address_field_id and replace 'ADDRESSFINDER_DEMO_KEY' with your AddressFinder account key.

### Step 7
Test the page.
