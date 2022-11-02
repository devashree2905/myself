# myself
Just me 
<!DOCTYPE html>
<html lang="en">
	<head>
		<meta charset="UTF-8" />
		<meta http-equiv="X-UA-Compatible" content="IE=edge" />
		<meta name="viewport" content="width=device-width, initial-scale=1.0" />
		<title>Library</title>
		<link rel="stylesheet" href="styles.css" />
	</head>
	<body>
		<div class="overlay no-display"></div>
		<header>
			<h1>Library</h1>
			<button class="add-book btn">Add Book</button>
		</header>
		<main>
			<form class="add-book-form no-display">
				<div class="form-header">
					<h3>Add a book</h3>
					<button class="close btn">&times;</button>
				</div>
				Name: <br />
				<input type="text" placeholder="Enter book name" class="title" /> <br />
				Author: <br />
				<input type="text" placeholder="Enter book author" class="author" />
				<br />
				Number of pages: <br />
				<input
					type="number"
					placeholder="Enter the number of pages"
					class="num-of-pages"
				/>
				<br />
				Read the book? <input type="checkbox" class="is-read" /> <br />
				<button type="submit" class="btn">Add Book</button>
			</form>
			<div class="books-grid"></div>
		</main>
		<script src="script.js"></script>
	</body>
</html
