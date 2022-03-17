function fizzbuzz() {
	var display = document.getElementById('display');
	var displayHTML = "";
	for (i = 1; i < 101; i++) {
		var num = "";
		if (i % 3 == 0) {
			num += "Fizz";
		}
		if (i % 5 == 0) {
			num += "Buzz";
		}
		displayHTML += "<p>" + (num == "" ? i : num) + "</p>";
	}
	display.innerHTML = displayHTML
}
