# Refine dashboard

A **Web application** for agents to register their properties for rent.

## **Interface**

-   The user can register with a google account:

![](https://cdn.discordapp.com/attachments/709539088302080074/1076922187514130564/image.png)

-   You can see statistics about you properties in the dashboard section

![](https://cdn.discordapp.com/attachments/709539088302080074/1076923330583597256/image.png)

-   You can visualize all the properties in the properties section

![](https://cdn.discordapp.com/attachments/709539088302080074/1076923874475778068/image.png)

-   For each card, you can see more details about it

![](https://cdn.discordapp.com/attachments/709539088302080074/1076924843418730546/image.png)

## **Installation**

For installation, just need to type the following commands:

```bash
cd client
npm install
cd ..
cd server
npm install
```

You will also need to create the following environmental variables:

-   `REACT_APP_GOOGLE_CLIENT_ID`
-   `MONGODB_URL`
-   `CLOUDINARY_CLOUD_NAME`
-   `CLOUDINARY_API_KEY`
-   `CLOUDINARY_API_SECRET`

## **Testing**

For testing, you nees to run the following commands in the right folders

-   For `client`

```bash
npm run dev
```

-   For `server`

```bash
npm start
```
