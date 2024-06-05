### Project 1 - Faded by Alan Walker (Musical Piece/Organized Sound)

This uses the simple Sine-Env-Piano tool to play a two-hand melody of Faded. Since playing both hands simulatenously on the laptop keyboard was complicated, I used the record feature to first record the left hand arpeggios. I then recorded a the right hand melody as a second layer, while the first layer was playing in the background. This created one audio with the affect that both hands are simulataneously playing. 

https://github.com/allolib-s24/notes-sharanyasharma21/assets/47366553/b0d6aa40-a004-40a8-8afc-95e189c2420a

### Project 2 - Nursery Rhyme Melody on Marimba using FM Synthesis (Sound Design)

This sound design project uses FM Synthesis to replicate the sound of a Marimba. By changing the idx1, idx2, idx3, carMul, and modMul parameters to the values shown below, I was able to replicate the sound of a Marimba and play the common nursery rhyme melody, "Row, Row, Row Your Boat".

<img width="221" alt="Screenshot 2024-06-04 at 9 52 22 PM" src="https://github.com/allolib-s24/notes-sharanyasharma21/assets/47366553/706647bf-6a57-4823-8426-9128e989942a">

https://github.com/allolib-s24/notes-sharanyasharma21/assets/47366553/e80b4b2c-ebe8-48e4-92b9-002f4b6859e1

### Project 3 - Frequency Multiplying Adjuster (Sound Design)

The purpose of this frequency adjuster is to allow the user to play their recorded piece in any octave desired. The freqMult parameter value of 1 maintains the original octave. Values greater than 1 increases the frequency resulting in a higher octave, and values less than 1 decreases the frequency resulting in a lower octave. This allows the user to experiment with their piece and also access frequencies that are not in the standard allolib SineEnv keyboard. Prior to this, the only way of playing a piece at different frequencies was by converting MIDI file notes that already existed in the file, or hardcoding the values of the frequencies in the script. The image below demonstrates using the playNote function to modify the parameters of each individual note, such that each note's frequency is multiplied by the freqMult value. Because the playNote funciton is called for each note, the playPiece function aggregates all the notes taking a parameter value for freqMult. Below is an image of how to implement this code. For this example, the freqMult value is 1, implying that the piece has retained its original frequency.

<img width="869" alt="Screenshot 2024-06-04 at 9 54 07 PM" src="https://github.com/allolib-s24/notes-sharanyasharma21/assets/47366553/9d7a2759-db91-4499-92a2-adc56387ef9d">

<img width="508" alt="Screenshot 2024-06-04 at 9 54 27 PM" src="https://github.com/allolib-s24/notes-sharanyasharma21/assets/47366553/180e4c60-3422-4594-8e1b-e5c5b5fd5f8b">

### Project 4 - Rondo Alla Turka Piano Sonata No.11 in A Major by Mozart (Musical Piece/Organized Sound)

This uses the Sine-Env-Piano tool to play a complicated melody. The piece was played using the laptop keyboard. 

### Project 5 - Spectrogram implementation for Rondo Alla Turka Piano Sonata No.11 (Final Project Part A)

This spectrogram uses the Short-Time-Fourier Transform to create an audioreactive spectrogram that constantly changes color based on the frequencies of the piece and changes the coordinates of the waves based on trigonometric combinations of the (x,y,z) coordinates.

https://github.com/allolib-s24/notes-sharanyasharma21/assets/47366553/e539faff-3dff-4292-bdc1-96339911a47b

### Project 6 - Spectrogram Tutorial (Final Project Part B)

The purpose of this project was to simplify the process of developing a spectrogram and provide a tutorial to those who would easily like to implement a spectrogram to their musical piece.

[Spectrogram Tutorial Final Project CS190D.pdf](https://github.com/user-attachments/files/15573267/Spectrogram.Tutorial.Final.Project.CS190D.pdf)



