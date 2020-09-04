<!-- 
### Exercise 1

1. Create a simple page having a header, main content, and a footer.

2. Inside the header keep the brand name to the left and all the navigation to the right.

3. Inside the main content take an article section having two columns. In the first column put a heading and some introductory text of the article and in the second column take an image. -->

<!DOCTYPE html>
<html>
<head>
	<title>Messi</title>
	<meta charset="utf-8">
	<link rel="stylesheet" href="assets/stylesheet/style.css">
</head>
<body>
	<header>
		<a href="https://altcampus.io">
			<img src="assets/media/messi2.png" alt="Messi">
		</a>			
		<nav class="nav">
			<a href="index.html">HOME</a>
			<a href="https://en.wikipedia.org/wiki/Lionel_Messi">ABOUT</a>
			<a href="https://www.themessistore.com/:~:text=Welcome%20to%20The%20Messi%20Store,the%20pitch%20to%20the%20apparel.">PAGE</a>
		</nav>
	</header>
	<main>
		<article>
			<div class="col-1">
				<h2>About Lionel Messi</h2>
				<p>Lionel Andrés Messi Cuccittin,Born and raised in central Argentina, Messi relocated to Spain to join Barcelona at age 13, for whom he made his competitive debut aged 17 in October 2004. He established himself as an integral player for the club within the next three years, and in his first uninterrupted season in 2008–09 he helped Barcelona achieve the first treble in Spanish football; that year, aged 22, Messi won his first Ballon d'Or. Three successful seasons followed, with Messi winning four consecutive Ballons d'Or, making him the first player to win the award four times and in a row.[10] During the 2011–12 season, he set the La Liga and European records for most goals scored in a single season, while establishing himself as Barcelona's all-time top scorer. The following two seasons, Messi finished second for the Ballon d'Or behind Cristiano Ronaldo (his perceived career rival), before regaining his best form during the 2014–15 campaign, becoming the all-time top scorer in La Liga and leading Barcelona to a historic second treble, after which he was awarded a fifth Ballon d'Or in 2015. Messi assumed the captaincy of Barcelona in 2018, and in 2019 he secured a record sixth Ballon d'Or</p>
				<p>An Argentine international, Messi is his country's all-time leading goalscorer. At youth level, he won the 2005 FIFA World Youth Championship, finishing the tournament with both the Golden Ball and Golden Shoe, and an Olympic gold medal at the 2008 Summer Olympics. His style of play as a diminutive, left-footed dribbler drew comparisons with his compatriot Diego Maradona, who described Messi as his successor. After his senior debut in August 2005, Messi became the youngest Argentine to play and score in a FIFA World Cup during the 2006 edition, and reached the final of the 2007 Copa América, where he was named young player of the tournament. As the squad's captain from August 2011, he led Argentina to three consecutive finals: the 2014 FIFA World Cup, for which he won the Golden Ball, and the 2015 and 2016 Copas América. After announcing his international retirement in 2016, he reversed his decision and led his country to qualification for the 2018 FIFA World Cup, and a third-place finish at the 2019 Copa América</p>
			</div>
			<div class="col-2">
				<img class="img" src="assets/media/lionel.jpeg" alt="Lionel_Messi">
			</div>
		</article>
	</main>
	<footer>
		<small>&copy;Messi10</small>
	</footer>
</body>
</html>