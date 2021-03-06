# PalpiteBox (Semana Fullstack Master)

Homepage
![Preview](https://github.com/RebecaPastl/palpite-box/blob/master/public/images/index.png)

About
![Preview](https://github.com/RebecaPastl/palpite-box/blob/master/public/images/about.png)

Contact
![Preview](https://github.com/RebecaPastl/palpite-box/blob/master/public/images/contact.png)
![Preview](https://github.com/RebecaPastl/palpite-box/blob/master/public/images/contactThankYou.png)

Customer satisfaction survey page
![Preview](https://github.com/RebecaPastl/palpite-box/blob/master/public/images/survey.png)

Coupon page
![Preview](https://github.com/RebecaPastl/palpite-box/blob/master/public/images/surveyPromoCode.png)

## Table of Contents
* [Description](#description)
* [Requirements](#requirements)
* [Deployment](#deployment)
* [Technologies](#technologies)
* [Author](#author)
* [License](#license)
* [Acknowledgements](#acknowledgments)

## Description

The Palpite-box project allows a customer to rate the service from a small business. The owner of the small business can access a spreadsheet where they have access to the filled information, share promocodes with the customers that have rated the service through Palpite-box, keep track of the used codes and the customers’ satisfaction with the business.

## Requirements

NodeJS and NPM are needed.

```
npm install
npm run dev
```

## Deployment
This Project can be deployed using Vercel.
It is necessary to create **environment variables** to access Google Sheets:
```
SHEET_CLIENT_EMAIL=service credential’s client email
SHEET_PRIVATE_KEY= service credential’s private key (all \n must be replaced by a new line and the whole key must be encoded in base64)
SHEET_DOC_ID=sheet address/id
```

## Technologies

* [NextJS](https://nextjs.org/) -The React Framework.
* [TailwindCSS](https://tailwindcss.com/) - A utility-first CSS framework for
rapidly building custom designs.
* [Figma](https://figma.com/) - Online prototyping tool.
* [Google Sheets](https://drive.google.com) - Googlesheets.
* [React Hook Form](https://react-hook-form.com/) - Form validator.

## Author

* **Rebeca Pastl** - [LinkedIn](https://www.linkedin.com/in/rebeca-pastl/)

## License

MIT License 
Copyright (c) [2020] [Rebeca Pastl].
For more information, read [LICENSE.md](LICENSE.md).

## Acknowledgments
* This project was developed during [DevPleno](https://devpleno.com/)’s Fullstack Master classes.
* [Icons](https://fontawesome.com/license) - Icons downloaded from [Font Awesome](https://fontawesome.com/) website.
* Images - Images from [Pexels](https://www.pexels.com/) website.
