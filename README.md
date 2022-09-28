# Automation

**Description**
Here I  wrote some lines of programming with which I tested a few features from a website.

describe('eMag.ro', () => {

it('should have the correct page title'), async () => {
  await browser.url('https://www.emag.ro');
  await expect(browser).toHaveTitle('eMAG.ro - Căutarea nu se oprește niciodată');
};
it('should contain a cart button', async () => {
const cartButton = await $('#my_cart');
await expect(cartButton).toBeDisplayed();
});
it('should open eMag Genius page' , async () =>{
const geniusButton = await $('[title="Genius"]');
await geiunsButton.click();
await expect(browser).ToHaveTitle('eMag.ro - Căutarea nu se oprește niciodată');
});
it('' , async () =>{
  const searchBox = await $('#searchboxTrigger');
  const searchButton = await $('.searchbox-submit-button');
  await searchBox,setValue('Trciou polo');
  await searchButton.click();
  await expect(browser).toHaveTitle('Cauti Tricou polo? Alege din oferta eMAG.ro');
});
    it('should load', async () => {
     
        await browser.url('http://www.emag.ro');

      
      const searchBox = await $('#searchboxTrigger');

      const helpLink = await $('.class="navbar-aux-help-link"');

      const firstButton = await $('.js-megamenu-list-department-link gtm_31vgamc"');

      helpLink.click();
    });do {
	
	
} while (condition);


});

