<!--Variabler-->
function udregn(){
	var dkk;
	var kurs;
	var resultat;
	var res;

  <!--Udregning af tidspunktet-->
	tidspunkt = document.form.tidspunkt.value;

    <!--Udregning af tidspunktet-->
	kilometer = document.form.kilometer.value;

  <!--If: Hvis tidspunktet er før kl 6, else if: Hvis tidspunktet er efter kl 6 og før kl 18, else: hvis tidspunkt er efter kl 18-->
	if (tidspunkt < 6) {
	   resultat = 52 + (kilometer*22);
	} else if (tidspunkt < 18) {
	   resultat = 33 + (kilometer*16);
	} else {
	   resultat = 47 + (kilometer*18);
	}
