# Privacy.com card embed stylesheet

_From [privacy.com developer documentation](https://developer.privacy.com/docs#pci-compliance)_
> Some API functionality returns full card PANs and CVV codes, and may require you to comply with the Payment Card Industry Data Security Standards (PCI DSS). Some clients choose to reduce their PCI obligations by leveraging our hosted iframe solution documented below.
> 
> In this setup, the API client can create and modify cards using a UUID token. PANs and CVV codes are presented to the end-user through a secure iframe hosted on api.privacy.com, stylized in the client's branding through a custom css stylesheet.
> 
> Card PANs and CVVs never touch the API client's servers, yet full card data can be displayed to their end-users.

This repo hosts the CSS for styling our Privacy.com hosted embeds.

`index.html` - this file is the default HTML provided by Privacy.com
`style.css` - this file is our custom CSS that is pulled by Privacy.com