# hoaxbust_gui

Hoaxbusters whatsapps with gui

## Requirements to run the code:

1. You need `python3` to run the code. The code requires the `tkinter` package which should be installed with most python platforms automatically. We also require the latest python imaging library (pillow >=6.2.2), install using 

```
pip install pillow
```

2. You need to download the Noto fonts from the [Google noto repository](https://www.google.com/get/noto/), email me if you need a link to select
Indian languages. Unzip and store in a directory named `Noto` within the
repository.

3. Download the translations csv file from google sheets and save it as `Hoaxbust2.csv`.

4. Modify `Master_config.yaml` to reflect fonts for desired language


## Running the code

```
python gui.py language
```

Select string by pressing `1` ("Claim:"), `2` (text of claim), `3` ("Verdict"), `4` (verdict of the text), `5` (more verbose verdict, this is often blank), `6` ("Why?"), `7` (the reasoning)

Increase or decrease the font size with `i` or `d`, respectively.

Increase or decrease the length of the string by using `l` or `s`, respectively.

Move to the next image by pressing `n`.

Save the placements and fonts file using `w` (this can be done at any stage).


