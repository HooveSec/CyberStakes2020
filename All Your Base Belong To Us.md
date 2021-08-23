# All Your Base Belong To Us
## Points: 50
#In honor of 30 years of terrible translations, we figured we'd give you a try at a series of (easier) translation problems. 
#All you have to do is to translate bases by connecting to challenge.acictf.com:52062. 
#In case you're new to network programs, we even have some Python starter code you can use.
### [Solution]
      I manually went through this by connecting to the port and server listed using netcat and when prompted to convert,
      I copy and pasted the conversions into the following 2 websites
      https://www.rapidtables.com/convert/number/hex-dec-bin-converter.html
      https://conv.darkbyte.ru/

      The prompt required 5  conversions that looked like this
      hex -> b64
      37236c6e4c7131792b4a495e57683b4c556b294c46795f3d2b3f34447b5e752934734a413b7147612a354e4050743544613b457b4d3477782832407354702d30

      Flag: ACI{Somebody_set_up_us_the_bomb_d9229a70}
