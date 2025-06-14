## Huggingface
1. Sign up to [https://huggingface.co/](https://huggingface.co/).
2. In the top‑right corner, click the ➕ icon → **New Space**.
3. **Name**: enter `dproxy` (or any name you prefer).
4. **SDK**: choose **Docker**
5. **Visibility**: select **Public**
6. Click **Create Space**.
7. In the Files section, upload the Dockerfile from this repo (or create a file in huggingface named Dockerfile and paste the contents of the Dockerfile of this repo), commit then wait for it to build, start and run.
8. Click **Embed this Space**. It will show you the url of the space. Visit that url. If you see a ":)" then you are good to go.
9. Channels playlist is accessible via: **https://username-dproxy.hf.space/playlist/channels**. (Refresh playlist from your iptv player to update)</br>
   Events playlist is accessible via: **https://username-dproxy.hf.space/playlist/events**. (Refresh playlist from your iptv player to update)
10. Enjoy! </br>
Note: To update the proxy for new changes, click on **Settings** then click on **Factory rebuild**.

## Vercel
1. Sign up to https://vercel.com/signup and select Hobby.
2. Once your account is fully setup and activated, click **Deploy** button. <br><br>
<a href="https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Fpigzillaaaaa%2Fdaddylive" target="_blank"><img src="https://vercel.com/button" alt="Deploy with Vercel"/></a>
3. Connect your github account to vercel, set the scope and set the repository name (eg. dproxy) then click **Create**
4. Wait for the project to build. If you see a ":)" then you are good to go.
5. Go to the dashboard and under **Domain**, copy the url (eg. https://dproxy-g327.vercel.app).
6. Channels playlist is accessible via: **https://dproxy-g327.vercel.app/playlist/channels**. (Refresh playlist from your iptv player to update)</br>
   Events playlist is accessible via: **https://dproxy-g327.vercel.app/playlist/events**. (Refresh playlist from your iptv player to update)
7. Optional: Change the **timeout (Function Max Duration)** and **location (Function Region)** in **Settings** -> **Functions**
8. Enjoy! <br>

## docker-compose
1. Clone the repository
   ```bash
   git clone https://github.com/pigzillaaaaa/daddylive
   cd daddylive
   ```
2. Launch the service:
   ```bash
   docker-compose up -d --build
   ```
3. Visit the proxy at:
   ```text
   http://localhost:7860  
4. Channels playlist is accessible via: **http://localhost:7860/playlist/channels**. (Refresh playlist from your iptv player to update)</br>
   Events playlist is accessible via: **http://localhost:7860/playlist/events**. (Refresh playlist from your iptv player to update)
5. Enjoy! (For arm cpus, visit https://github.com/pigzillaaaaa/daddylive/issues/10)


