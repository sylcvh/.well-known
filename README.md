# 🔗 Linking a GitHub Pages Domain to Discord Connections

Verify ownership using the **HTTPS (file method)** with a simple `.well-known` repository.

### Step-by-Step Guide 🚀

1. Open Discord and click the **gear icon** next to your username to open **User Settings**.  
2. In the sidebar, select **Connections**.  
3. Click the **domain icon** (🌐), enter your GitHub Pages domain, and click **Next**.  
4. Choose **Verify using HTTPS**.  
5. Copy the provided verification text (e.g., `dh=123456abc`).  

> [!WARNING]  
> **Do not close the pop-up!** Keep it open until verification is complete.

6. [Fork this repository](https://github.com/sylcvh/.well-known/fork)  
   *(Alternatively, create a new repository if you prefer.)*

> [!IMPORTANT]  
> **Do not change the repository name** — it must remain exactly **`.well-known`**.

7. In the root of the repository:  
   - Edit the file named **`discord`**  
   - Replace its entire content with the text you copied in step 5  
   - Commit the changes  

8. Go to **Settings → Pages** in your repository:  
   - Under **Branch**, select the `main` branch (or `master`) and `/ (root)` folder  
   - Click **Save**  
   GitHub Pages will deploy automatically.

9. Return to the Discord pop-up and click **Verify**.  
   Your domain should now appear on your profile! 🎉

---

If this guide was helpful, please consider **starring ⭐** the repository. Thank you!
