# EAFC VirtualPro Studio

Welcome to VirtualPro Studio, the ultimate customization tool for your Virtual Pro in EA SPORTS FC. This web service allows you to meticulously craft your player's attributes, explore various skill trees, and save your ideal football player builds.

## Features

- **Interactive Skill Tree:** Unlock skills and adjust your Virtual Pro's abilities based on your gameplay style.
- **Customizable Builds:** Tailor the height, weight, and position attributes to fit your strategic needs.
- **Performance Simulation:** See how different configurations affect your Pro's performance on the field.
- **Save and Share:** Keep your favorite builds and share them with the community to see who builds the best Virtual Pro.

## Contributing
Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

- Fork the Project
- Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
- Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
- Push to the Branch (`git push origin feature/AmazingFeature`)
- Open a Pull Request

## Development

### Install Dependencies

First of all we need to install dependencies, run in terminal
```
pnpm install
```

### PNPM Scripts

* 🔥 `start` - run development server
* 🔧 `dev` - run development server
* 🔧 `build` - build web app for production

### Vite

There is a [Vite](https://vitejs.dev) bundler setup. It compiles and bundles all "front-end" resources. You should work only with files located in `/src` folder. Vite config located in `vite.config.js`.

### PWA

This is a PWA. Don't forget to check what is inside of your `service-worker.js`. It is also recommended that you disable service worker (or enable "Update on reload") in browser dev tools during development.

### Assets

Assets (icons, splash screens) source images located in `assets-src` folder. To generate your own icons and splash screen images, you will need to replace all assets in this directory with your own images (pay attention to image size and format), and run the following command in the project directory:

```
framework7 assets
```

Or launch UI where you will be able to change icons and splash screens:

```
framework7 assets --ui
```

### Documentation & Resources

* [Framework7 Core Documentation](https://framework7.io/docs/)
* [Framework7 Vue Documentation](https://framework7.io/vue/)


* [Framework7 Icons Reference](https://framework7.io/icons/)
* [Community Forum](https://forum.framework7.io)



## License
Distributed under the GPL License. See `LICENSE` for more information.

## Contact
Your Name - [@yourtwitter](https://twitter.com/yourtwitter) - email@example.com
Project Link: [https://github.com/yourusername/virtualpro-studio](https://github.com/yourusername/virtualpro-studio)

This README provides a basic blueprint for setting up, using, and contributing to VirtualPro Studio. Adjust the sections as necessary to fit the specifics of your project and team policies.
