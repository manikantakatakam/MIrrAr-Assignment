
# High-Level Test Cases

1. **Camera Accessibility Test:**
   - Cannot access the camera while allowed permission for camera access in the Camera Mode for jewelry try-on.
   - Tested on different devices and browsers.
     
     ![Placeholder Image](https://github.com/manikantakatakam/personal_practise/blob/09eb8b01a9e5e316011bf432eef4e213b3e66eb5/today%20testing/Camera_issue.png)
     
     
2. **Model Switching in Eyewear Test:**
   - In Model Mode for eyewear, test the ability to switch from one model to another.
   - Verify that the switch is smooth and accurate.

3. **There is no model available for the Handbag Test:**
   - Make Sure that there is a model present to do a real-try-on for Handbags.
   - In present models, we can't find the full body.
   - So, add a model with a full body so that we can do a real-try-on for Handbags too.   

4. **Realistic Try-On for Eyewear Test:**
   - Specifically for eyewear products, test the realism of the try-on experience.
   - Ensure that the eyeglasses align properly on the user's face rather than just placing an image.

5. **Studio 3D View Test:**
   - In Studio Mode, check if a whole 3D view is available for all products except eyewear.
   - Verify that users can see detailed views of each product.

# Bug Report 

## Bug 1: Unable to Access Camera

**Steps to Reproduce:**
1. Open the application and navigate to the Try-On section.
2. Select Camera Mode to try on jewelry.
3. Attempt to try on any jewelry item.

**Expected Result:**
   - The camera should activate, and the selected jewelry item should appear realistically on the user.

**Actual Result:**
   - The camera fails to activate, and the try-on process does not initiate.
   - The application may display an error message or freeze.

**Environment:**
   - Device: [Lenovo Ideapad 310 RAM 4GB ROM 1TB ]
   - Browser/Platform: [Chrome Latest version]
   - Network: [30mbs good network connectivity]

**Severity:**
   - Critical (as it affects a core functionality of the product)

**Attachments:**
  ![Placeholder Image](https://github.com/manikantakatakam/personal_practise/blob/09eb8b01a9e5e316011bf432eef4e213b3e66eb5/today%20testing/Camera_issue.png)

## Bug 2: Model Switching Issue in Eyewear Mode

**Steps to Reproduce:**
1. Open the application and navigate to the Model Mode for eyewear.
2. Attempt to switch from one model to another.

**Expected Result:**
   - The application should smoothly transition from one model to another.

**Actual Result:**
   - Model switching is either slow, inaccurate, or non-functional.
   - Users may experience delays or errors during the switching process.

**Environment:**
   - Device: [Lenovo Ideapad 310 RAM 4GB ROM 1TB ]
   - Browser/Platform: [Chrome Latest version]
   - Network: [30mbs good network connectivity]
     
**Severity:**
   - Moderate (as it affects the user experience in a specific mode)
**Attachments:**
  ![Placeholder Image](https://github.com/manikantakatakam/personal_practise/blob/09eb8b01a9e5e316011bf432eef4e213b3e66eb5/today%20testing/Eyewear_model_view.png)
## Bug 3: Except eyewear can't do 360 view for all products.

**Steps to Reproduce:**
1. Open the application and navigate to the Studio.
2. Select products other than eyewear.
3. try to view 360 of those products.

**Expected Result:**
   - Should be able to see the 360 view of all products.

**Actual Result:**
   - 360 view is  inaccurate, or non-functional.
   - Users will experience that they are unable to move those products around in 360 view.

**Environment:**
   - Device: [Lenovo Ideapad 310 RAM 4GB ROM 1TB ]
   - Browser/Platform: [Chrome Latest version]
   - Network: [30mbs good network connectivity]
     
**Severity:**
   - Moderate (as it affects the user experience in a specific mode)

**Attachments:**
   - ![Placeholder Image](https://github.com/manikantakatakam/personal_practise/blob/09eb8b01a9e5e316011bf432eef4e213b3e66eb5/today%20testing/mangalsutras_StudioView.png)

## Bug 4: Some of the products did not have an image of the product.

**Steps to Reproduce:**
1. Open the application and navigate to the try-on.
2. Select the product sets.
3. While you are scrolling down you can find a product with no image loaded.

**Expected Result:**
   - Should be able to view image of the product.

**Actual Result:**
   - no image is loaded for those products.

**Environment:**
   - Device: [Lenovo Ideapad 310 RAM 4GB ROM 1TB ]
   - Browser/Platform: [Chrome Latest version]
   - Network: [30mbps good network connectivity]
     
**Severity:**
   - Moderate (as it affects the user experience in a specific mode)

**Attachments:**
   - ![Placeholder Image](https://github.com/manikantakatakam/personal_practise/blob/4a97994f31a658cba750fff98e544265049ecffb/today%20testing/no_image_model_view.png)
