![PayPal Developer Cover](https://github.com/paypaldev/.github/blob/main/pp-cover.png)

<div align="center">
  <a href="https://twitter.com/paypaldev" target="_blank">
    <img alt="Twitter: PayPal Developer" src="https://img.shields.io/twitter/follow/paypaldev?style=social" />
  </a>
  <br />
  <a href="https://twitter.com/paypaldev" target="_blank">Twitter</a>
    <span>&nbsp;&nbsp;-&nbsp;&nbsp;</span>
  <a href="https://www.paypal.com/us/home" target="_blank">PayPal</a>
    <span>&nbsp;&nbsp;-&nbsp;&nbsp;</span>
  <a href="https://developer.paypal.com/home" target="_blank">Docs</a>
    <span>&nbsp;&nbsp;-&nbsp;&nbsp;</span>
  <a href="https://github.com/paypaldev" target="_blank">Code Samples</a>
    <span>&nbsp;&nbsp;-&nbsp;&nbsp;</span>
  <a href="https://dev.to/paypaldeveloper" target="_blank">Blog</a>
  <br />
  <hr />
</div>

# PayPal Advanced Checkout Tutorial

This is the example code for the YouTube video, [How to Integrate PayPal Advanced Checkout](https://www.youtube.com/watch?v=pHbeILqVjOk)

## Getting Started

Grab your PayPal CLIENT ID and SECRET and fill them in the following files:

- [.env](https://github.com/rauljr7/ppcp_advanced_acdc_tutorial/blob/main/.env)
- [script.js](https://github.com/rauljr7/ppcp_advanced_acdc_tutorial/blob/main/script.js)
- If you want to use a port other than 3000, make sure you adjust the [.env file here](https://github.com/rauljr7/ppcp_advanced_acdc_tutorial/blob/main/.env#L1) and also adjust that in the main javascript file in these locations:
  - [script.js#L30](https://github.com/rauljr7/ppcp_advanced_acdc_tutorial/blob/main/script.js#L30), [script.js#L97](https://github.com/rauljr7/ppcp_advanced_acdc_tutorial/blob/main/script.js#L97), [script.js#L108](https://github.com/rauljr7/ppcp_advanced_acdc_tutorial/blob/main/script.js#L108), [script.js#L140](https://github.com/rauljr7/ppcp_advanced_acdc_tutorial/blob/main/script.js#L140), [script.js#L206](https://github.com/rauljr7/ppcp_advanced_acdc_tutorial/blob/main/script.js#L206)
- If you want to use SendGrid for sending emails, add your SendGrid API Key in the [index.js file here](https://github.com/rauljr7/ppcp_advanced_acdc_tutorial/blob/main/index.js#L160) and you can edit the email HTML content in the [email_content_html variable here](https://github.com/rauljr7/ppcp_advanced_acdc_tutorial/blob/main/index.js#L161)

Once you have configured your credentials, you can run `npm i` to install the packages and start your app with `node index`

## PayPal Developer Community

The PayPal Developer community helps you build your career, while also improving PayPal products and the developer experience. You’ll be able to contribute code and documentation, meet new people and learn from the open source community.

- Website: [developer.paypal.com](https://developer.paypal.com)
- Twitter: [@paypaldev](https://twitter.com/paypaldev)
- Github: [@paypal](https://github.com/paypal)
