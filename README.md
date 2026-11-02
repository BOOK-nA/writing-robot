# Writing Robot

Name: Anurak Narak
Student ID: 690631040

## Files

| File | What it is |
|---|---|
| `writing_robot.ipynb` | The main notebook. It is saved with all outputs, so you can see the results without running it. |
| `interactive/` | Two web pages: the drawing tool and the keyframe demo. Download the files and open it in a browser. |
| `results/` | Demo video link and result figures |
| `Writing_Robot_Anurak_Narak_690631040.pdf` | Presentation slides (pdf file has no interactive html file, prefer in canva) |
| `Slide_in_Canva_Link.txt` | Slide in canva |
| `requirements.txt` | Python packages |

## How to run

1. Install the packages: `pip install -r requirements.txt`.
2. Open `writing_robot.ipynb` in Jupyter and run all cells.
   Open the Meshcat link from the first cells to watch the robot.
3. The full notebook takes about 10 minutes, including the experiment in Section 10.

To use your own drawing, open `interactive/Chalk Drawing Board.html` in a browser, draw, click **Copy**,
and paste the JSON into `STROKES_JSON` in Section 4.

## Credits

- R. Tedrake, *Robotic Manipulation*, https://manipulation.csail.mit.edu (Ch. 2, 3, 6, 8) and the course notebooks.
- `MeshcatWriter` is adapted from `book/force/writing.ipynb` of the course.

