# data-science-colour
The goal of this project is to create a code for analysing colour difference through measuring Euclidean distance between RGB terms. The datasets used compare averaged RGB colours labelled by human perception to the X11 list of hundreds of predefined RGB values with unique colour labels.

The first data set used is X11 developed by MIT for computer display systems X11and the second from averages calculated from [colour naming] data (http://colournaming.org). m. I give a measurement of the difference between the X11 reference list and named colours by calculating the 3D Euclidean distance in x,y,z space between two RGB points colour difference. This information is represented visually in a bar chart showing distances between RGB values between the datasets. I have also included a visual comparison for each representation of the user's colour terms.

Finally, I calculate the complementary colours for each colour term for both versions. Complementary colours are considered a colours opposite since they cancel to white, so this provides a visual representation of difference for comparison.

My results indicate a gap between users recognition of colours and the X11 lists that is not consistent across colours. Further insight into these colour differences can be drawn by reference to the calculated complementary colours. I consider various interpretations of such a colour differece including language and the repective purposes of colour naming for humans and computers.
