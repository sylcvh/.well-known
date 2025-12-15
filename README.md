# Linking a GitHub Pages Domain to Discord Connections

Add your domain to your Discord connections to showcase it on your profile.

We will verify it using **HTTPS (file method)**.

### Step-by-Step Guide

1. Open Discord and navigate to your user settings by clicking on the gear icon next to your username.  
2. In the settings menu, select **Connections**.  
3. Click the **domain icon**; a pop-up will appear. Enter your GitHub Pages domain name.  
4. Click on **Next**, then select **Verify using HTTPS**.  
5. Copy the content provided there (something like `dh=123456abc`).  
   **DON'T CLOSE THE POP-UP** — leave it open until verification is complete!  
6. [Fork this repository](https://github.com/sylcvh/.well-known/fork) (you can also create a new repository if preferred).

> [!IMPORTANT]
> Do not change the repository name; keep it exactly as **.well-known**.

7. Edit the `discord` file in the root of the repository and replace its content with the text you copied in step 5. Commit the changes.  
8. Go to **repository settings** → **Pages** and enable GitHub Pages for your forked repository (set the source to the `main` branch and `/ (root)` folder).  
9. Return to the Discord pop-up and click the **Verify** button. The domain will be added to your Discord profile!

---

If this guide was helpful, please consider **starring** this repository. Thank you! ⭐