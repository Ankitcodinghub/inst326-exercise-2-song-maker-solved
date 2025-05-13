# inst326-exercise-2-song-maker-solved
**TO GET THIS SOLUTION VISIT:** [INST326 Exercise 2-Song maker Solved](https://www.ankitcodinghub.com/product/inst326-exercise-2-song-maker-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;93569&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;INST326 Exercise 2-Song maker Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
# Background

For this exercise we are going to create a simple Song class. The song will contain data pertaining to the artist who performs the song, the name of the song, the beats per minute, and the notes that are in the song.

# Notes

– The name of your file should be song_maker.py.

– his exercise does not require the use of command line arguments.

# Instructions

**Write a class named Song.**

– Write an init() method with self, name(str), primary_artists(list), bpm(int) and chords(list) as the parameters. This method should to the following:

– Set an attribute name (representing the song’s name) to the name

– Set an attribute artists (representing the artists that perform that song) to a dictionary containing two keys(primary_artist and features). Each key’s value is a list. Add all the values from the primary_artists parameter to the value of the primary artist key. The value of features should remain empty for now.

– Set an attribute bpm (representing the beats per minute/tempo of the song) to the bpm

parameter.

Set an attribute chords (representing a list of chords that the song is comprised of ) to the

parameter chords.

– Write an associated_artists() method with the parameters self and other_artists. Other_artists should take a string value. This method should do the following:

– Append the other_artists parameter to the value of the features key of the artists

attribute.

– Write a change_beat() method with the parameters self, increase and change. Increase should take a boolean value; give it a default value of True. Change should take an integer type; give it a default value of 5. This method should do the following:

– Increase the bpm attribute by the amount of the parameter change if increase is True.

– Decrease the bpm attribute by the amount of the parameter change if increase is False.

– Write a modulate() method with the parameters self and steps. Steps can take an integer or a float; give it the default value 1. This method should do the following:

– Create a list containing all of the notes in the chromatic scale. They are:

– C’,’C#’,’D’,’D#’,’E’,’F’,’F#’,’G’,’G#’,’A’,’A#’,’B’

– Create an empty list, this list will hold the modulated chords.

– The method should then determine the correct modulated chord from the list given the index position of the starting chord and the step value.

– In music, a single step corresponds to two “half steps” away from the starting chord. Meaning, if I modulate “C” 1 step, the resulting chord will be “D”. If I modulate “C” .5 steps, the resulting chord will be “C#”.

– The method should append all new modulated chords to the empty list created earlier and set the chords attribute to this new list of modulated chords.

– Write an info() method with one parameter self. This method should return a single string

which contains a message letting the user know the songs name, artists, chords and beats

per minute.

– Write docstrings for each method. (__init__() doesn’t need a docstring.)

– Write an if __name__ == “__main__”: statement in which you create an instance of your class and invoke each method (you don’t have to explicitly invoke __init__()). You may wanna print the returned value of the info() method for testing the output of your script.
