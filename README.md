<!DOCTYPE html>
<html lang="en">

<head>
        <meta charset="UTF-8">
        <meta name="author" content="Koppány Márk">
        <meta name="description" content="Learning HTML from the beginning.">
        <meta name="viewport" content="width=device-width, initial-scale=1">
<title>Harry Potter - Hogwarts Legacy</title>
<link rel=icon href="harrypotter.png" type="image/x-icon">
<link rel="stylesheet" href="style.css" type="text/css">
    </head>
    
<body>
<header>
        <h1>Harry Potter - Hogwarts Legacy</h1>

    <nav aria-label="primary-navigation">
        <ul>
           <li>
             <a href="#introduction">Introduction to the game.</a> 
           </li>

           <li>
            <a href="#MTs">Expanding your inventory</a>
           </li>

           <li>
            <a href="#locations">Famous Locations</a>
           </li>

           <li>
            <a href="#creatures">Enemies you may encounter</a>
           </li>

           <li>
            <a href="#aboutyou">About you</a>
           </li>

        </ul>
    </nav>
</header>

        <hr>

    <main>
        
        <article id="introduction">
        <h2 class="fifty">You've just got the letter of your dreams.</h2>
        <p>Hogwarts awaits.</p>
        <video src="gameplaytrailer.mp4" width="600" height="300" controls autoplay muted>
        </video>
            <section>
        <h3>Your daily schedule as a wizard.</h3>
        <p>Let me tell you how you are going to:</p>
        <ol>
            <li>...Attend potion class.</li>
            <li>...Plant mallowsweet.</li>
            <li>...Cast new spells.</li>
        </ol>

    <figure>
        <img src="images/potionclass2.jpg" alt="Potion Classroom" title="The Potion Classroom"
        width="600" height="300" loading="lazy">
        <figcaption>Potions are useful in combat</figcaption>
    </figure>

    <table>
        <caption>Wizardly Schedule</caption>
        <thead>
        <tr>
            <th>&nbsp;</th>
            <th scope="col">Time</th>
            <th scope="col">Activity</th>
        </tr>
        </thead>
        <tbody>
        <tr>
            <th scope="row">Morning</th>
            <td>
                <time datetime="10:00">10am</time>-<time datetime="11:00">11am</time>
            </td>
            <td>Attend classes</td>
        </tr>
        <tr>
            <th scope="row">Afternoon</th>
            <td>
                <time datetime="11:00">11am</time>-<time datetime="15:00">15pm</time>
            </td>
            <td>Visit Hogsmeade</td>
        </tr>
        <tr>
            <th>Evening</th>
            <td>
                <time datetime="15:00">15pm</time>-<time datetime="19:00">19pm</time>
            </td>
            <td>Help the hamlets' people</td>
        </tr>
        <tr>
            <th scope="row">Night</th>
            <td rowspan="2">All Other Times</td>
            <td>Spend time in the Room of Requirement</td>
        </tr>
        <tr>
            <th scope="row">Anytime</th>
            <td>Hunt treasures in vaults</td>
        </tr>
    </tbody>
    <tfoot>
        <tr>
            <td colspan="3">This schedule is only an example, feel free to manage your time as you wish.</td>
        </tr>
    </tfoot>
    </table>

            </section>
        </article>

        <hr>

<article id="MTs">
    <h2 class="fiftyfive">Open world game, many collectable items.</h2>
    <section>
    <h3 class="wider" >You will find several gear items during your adventure.</h3>
        <p>Therefore, you have to make more space in your <em>inventory</em>.</p>
        <p>To achieve that, you need to do as much <abbr title="Merlin Trials">MTs</abbr> as possible.</p>
        <p><a href="https://www.polygon.com/hogwarts-legacy-guide/23601511/merlin-trial-location-mallowsweet-solution-inventory-storage-space-expansion" target="_blank">Here</a> you can see where to find and solve all of them.</p>
        <aside>
            <details>
                <summary>Guess the <mark>number of Merlin Trials</mark> in the game!</summary>
                <p>There are <span class="mtnumber">95 Merlin Trials scattered on the map</span>.</p>
            </details>
        </aside>
    </section>
</article>

<article id="locations">
        <h3>Locations in Hogwarts Legacy</h3>
        <ul>
        <li><p>There are plenty of special places in the game worth visiting.</p></li>
        <li><p>I've heard good things about <span class="hogsmeade">Hogsmeade</span>. Just to mention some:</p>

        <figure>
            <img src="images/hogsmeade.jpg" alt="Hogsmeade" title="Hogsmeade" 
            width="600" height="300">
            <figcaption>It's always cozy in Hogsmeade</figcaption>
        </figure>

        <address>
            Tomes and Scrolls Flying Page<br>
            Ollivanders Wands Shop<br>
            Community Garden
        </address>

    <figure>
        <img src="images/hogsmeademap.jpg" alt="Map of Hogsmeade" title="Map of Hogsmeade" 
        width="600" height="300" loading="lazy">
      <figcaption>Map of Hogsmeade and its vicinity</figcaption>
    </figure>
    </li>
    </ul>
</article>

<article id="creatures">

        <h3>Dangerous Creatures and Enemies</h3>
        <section>
            <h4>Monsters</h4>
       <dl>
        <dt>Trolls</dt>
        <dd><span class="descOne">Beware, they are <strong>strong</strong> and have a lot of HP. Of course it is no such
        a big deal for a skilled and experienced wizard, especially if you have the knowledge of 
        Avada Kedavra. Apart from that instant death spell, you can still beat the hell out of
        them, just don't forget to collect their boogeys.</span></dd>

        <dt>Spiders</dt>
        <dd><span class="descOne">The bigger, the more dangerous they are. In case if you have arachnophobia I recommend
            you to avoid the Forbidden Forest and those places where you can spot webs.</span></dd>

        <dt>Dugbogs</dt>
        <dd><span class="descOne">Toad-like creatures with powerful dash and strike with their tongue. Do not expect
            a very intense and spectacular fight, just cast your spells and deal damage, because
            they are annoyingly massive.</span></dd>
        </dl>
    </section>
    <section>
        <h4>Enemies</h4>
    <dl>
        <dt>Ashwinders</dt>
        <dd>Members of Rookwood Gang, who were <strong>dark wizards</strong>.</dd>

        <dt>Goblins</dt>
        <dd>Another foes who serve their leader, Ranrok.</dd>

        <dt>Pensieve Soldiers</dt>
        <dd>Dedicated to protect the pensieve, which is a very rare magical device.</dd>
    </dl>
    </section>
</article>

<hr>

<article id="aboutyou">
    <h2 class="twenty">About you</h2>
    <p>Share your thoughts on the game with me!</p>
    
    <form action="https://httpbin.org/get" method="get">
        <fieldset>
            <legend>Personal Information</legend>

    <p>
        <label for="firstName">First Name:</label>
        <input type="text" name="firstName" id="firstName" placeholder="Adrián" autocomplete="on" 
        required autofocus> 
    </p>
    <p>
        <label for="lastName">Last Name:</label>
        <input type="text" name="lastName" id="lastName" placeholder="Pauska" autocomplete="on" 
        required> 
    </p>
    <p>
        <label for="password">Password:</label>
        <input type="password" name="password" id="password" placeholder="cujo123" 
            required> 
    </p>
    <p>
        <label for="phone">Phone:</label>
        <input type="tel" name="phone" id="phone" placeholder="+3620..." pattern="^\+[0-9]{11}$"
            required> 
    </p>
    <p>
        <label for="year">Favorite Year as a Gamer:</label>
        <input type="number" name="year" id="year" min="2000" max="2023" step="1" value="2010">
    </p>
    <p>
        <label for="spell">Favorite Spell:</label>
        <select name="spell" id="spell" multiple size="7">
            <optgroup label="essentials">
                <option value="alohomora" selected>Alohomora</option>
                <option value="revelio">Revelio</option>
                <option value="protego">Protego</option>
            </optgroup>
            <optgroup label="control">
            <option value="glacius">Glacius</option>
            <option value="transformation">Transformation</option>
            <option value="levioso">Levioso</option>
            <optgroup label="damage">
            <option value="incendio">Incendio</option>
            <option value="confringo">Confringo</option>
            <option value="expelliarmus">Expelliarmus</option>
             </optgroup>
            <optgroup label="unforgivable curses">
                <option value="avadakedavra">Avada Kedavra</option>
                <option value="crucio">Crucio</option>
                <option value="imperio">Imperio</option>
            </optgroup>
            <option value="other">Other</option>
        </select>
    </p>
    <p>
        <label for="house">Favorite House:</label>
        <input type="text" name="house" id="house" list="house-list">
        <datalist id="house-list">
            <option value="Hufflepuff">
            <option value="Ravenclaw">
            <option value="Slytherin">
            <option value="Gryffindor">
        </datalist>
    </p>
</fieldset>

<br>

<fieldset>
    <legend>Who is your favorite character?</legend>
    <p>
    <input type="radio" name="characters" id="sebastian" value="sebastian">
    <label for="sebastian">Sebastian Sallow</label>
    </p>
    <p>
        <input type="radio" name="characters" id="poppy" value="poppy">
        <label for="poppy">Poppy Sweeting</label>
    </p>
    <p>
        <input type="radio" name="characters" id="natsai" value="natsai">
        <label for="natsai">Natsai Onai</label>
     </p>
    <p>
        <input type="radio" name="characters" id="other" value="other">
        <label for="other">Other</label>
    </p>
</fieldset>

<br>

<fieldset>
    <legend>Do you have favorite beast?</legend>
    <p>
        <input type="checkbox" name="beast" id="unicorn" value="unicorn">
        <label for="unicorn">Unicorn</label>
    </p>
    <p>
        <input type="checkbox" name="beast" id="mooncalf" value="mooncalf">
        <label for="mooncalf">Mooncalf</label>
    </p>
    <p>
        <input type="checkbox" name="beast" id="thestral" value="thestral">
        <label for="thestral">Thestral</label>
    </p>
    <p>
        <input type="checkbox" name="beast" id="otherBeast" value="otherBeast">
        <label for="otherBeast">Other</label>
    </p>
</fieldset>

<br>

<fieldset>
    <legend>Send Me An Owl</legend>
    <label for="message">Your Message:</label>
    <br>
    <textarea name="message" id="message" cols="30" rows="10"
     placeholder="I think the Giant Purple Toad looks like Apuska..."></textarea>
<br>

</fieldset>
<button type="submit">Submit</button>
<button type="reset">Reset</button>
</form>
</article>
</main>

        <hr>

    <footer>
        <p>
            &lt;&lt;&lt; &copy; <a href="about.html">Koppány Márk</a> &gt;&gt;&gt;
        </p>

        <p>
            <a href="#">Back to Top</a>
        </p>
    </footer>

        </body>
        </html>
