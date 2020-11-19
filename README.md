console.log("Hello i am a movie recomendation bot");
async function respond(inputText) {
	var result = await CampK12.classify("Movie recomendation model", inputText);
	var a = ["Dhoom2", "war", "Mission impossible", "commando", "Baaghi3"];
	var c = ["3 idiots", "fukrey", "fukrey returns", "Phir hera pheri", "Hungama"];
	var h = ["conjuring", "conjuring2", "Annabel", "veronica", "IT"];
	var t = ["talash", "drishyam", "mom", "specia26", "December 31"];
	if (result == "Action") {
		console.log(a[0]);
		console.log(a[1]);
		console.log(a[2]);
		console.log(a[3]);
		console.log(a[4]);
	}
	else if (result == "Comedy") {
		console.log(c[0]);
		console.log(c[1]);
		console.log(c[2]);
		console.log(c[3]);
		console.log(c[4]);
	}
	else if (result == "Horror") {
		console.log(h[0]);
		console.log(h[1]);
		console.log(h[2]);
		console.log(h[3]);
		console.log(h[4]);
	}
	else if (result == "Thriller") 
		console.log(a[0]);
		console.log(t[1]);
		console.log(t[2]);
		console.log(t[3]);
		console.log(t[4]);
	}
