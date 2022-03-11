<!-- Headers -->
# h1
## h2
### h3
#### h4
##### h5
###### h6

<!-- Bold -->
**Bold** <br>
__Bold 2__<br>
<b>Bold 3</b>

<!-- İtalic -->
*İtalic* <br>
_İtalic_

<!-- StireThrough -->
~~Üstü çizili~~

<!-- Quoting -->
>"Yattığın yerden para kazanmıyosan, zengindeğilsindir."

<!-- Links -->
[Link Github](https://github.com/eyytii) <br>
[Def Twitter] <br>
<a href="https://www.reddit.com/user/EyyTii2314">HTML tag Reddit</a>

<!-- Tabel -->
<body>
    <h2 style="color: #319d5a;">All input tags</h2>
    <form action="ornek1.php" method="POST">
        <label for="favcolor">Select your favorite color:</label>
        <input type="color" id="favcolor" name="favcolor"><p></p>
        <label for="bithday">Birthday:</label>
        <input type="date" id="birthday" name="birthday"><p></p>
        <label for="birthdaytime">Birthday (date and time):</label>
        <input type="datetime-local" id="birthdaytime" name="birthdattime"><p></p>
        <label for="mail">Enter Your Mail:</label>
        <input type="email" name="mail" id="mail"><p></p>
        <label for="myfile">Select your file:</label>
        <input type="file" id="myfile" name="myfile"><p></p>
        <label for="fname">First name:</label>
        <input type="text" id="fname" name="fname" required><p></p>
        <input type="hidden" id="custID" name="custID" value="3487">
        <label for="bdaymonth">Birthday (month and year)</label>
        <input type="month" id="bdaymonth" name="bdaymonth"><p></p>
        <label for="quantity">Quantity (Between 1 and 5):</label>
        <input type="number" name="quantity" id="quantity" min="1" max="5"><p></p>
        <label for="quantity">Quantity:</label>
        <input type="number" name="quantity" id="quantity" min="0" max="100" step="10" value="30"><p></p>
        <label for="vol">Volume (Between 0 and 50):</label>
        <input type="range" id="vol" name="vol" min="0" max="50"><p></p>
        <label for="gsearch">Search Google:</label>
        <input type="search" id="search" name="search"><p></p>
        <label for="phone">Enter Your phone number:</label>
        <input type="tel" id="tel" name="tel" pattern="[0-9]{3}-[0-9]{2}-[0-9]{-}"><p></p>
        <label for="homepage">add your homepage:</label>
        <input type="url" id="homepage" name="homepage"><p></p>
        <label for="week">Select a week:</label>
        <input type="week" id="week" name="week"><p></p>
        <input type="submit" value="submit">
    </form>
</body>


<!-- Def -->
[Def-Twitter]: https://twitter.com/LuWe_exe