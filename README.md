<html>
	<div id="product_name">Kacamata</div>
	<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>
	<script language="JavaScript">
		var product_name = $('#product_name').text()
		var phone = ['6281312020954','6281312020941','6281312020938']
		var i = parseInt(Math.random() * 3)
		var button = ('<a id="addToCartButton" href="https://api.whatsapp.com/send?phone='+phone[i]+'&text=Halo%20Supply,%20tertarik%20dengan%20'+product_name+'" class="action_button randombutton" onclick="window.confirmOptIn()">Beli Melalui WhatsApp</a>');
		document.write(button);
	</script>
</html>
