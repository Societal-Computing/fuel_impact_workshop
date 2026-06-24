# How to run the workshop 🚀

### Easiest: the one-click link 🔗
If your instructor sent you a **"Open in Colab"** link, just click it → press
**Runtime → Run all** → done. The data loads itself. *(You'll need a free Google
account.)* If you have that link, you can stop reading here.

If you only got this folder as a zip, use one of the two ways below.

---

## Option A — Google Colab (nothing to install, works on any laptop/Chromebook) ✅ easiest

1. Go to **<https://colab.research.google.com>**.
2. **File → Upload notebook**, and choose **`workshop.ipynb`**.
3. Run the **first cell** (click it, press **Shift + Enter**). It will ask you to
   **upload the data** — pick the file **`data.zip`** from this folder.
4. That's it — keep running the cells from top to bottom. 🎉

> You need a free Google account. Each person can run their own copy.

---

## Option B — Your own computer (if you have Python installed)

1. **Unzip** this folder somewhere you can find it.
2. Open a **terminal / command prompt** *inside* the unzipped folder.
3. Install the four small libraries we use:
   ```
   pip install -r requirements.txt
   ```
   *(If you use **Anaconda**, you already have all of them — you can skip this.)*
4. Start Jupyter and open the notebook:
   ```
   jupyter lab        # or:  jupyter notebook
   ```
   then click **`workshop.ipynb`**.

> Important: start Jupyter **from inside this folder**, so the notebook can find
> the `data/` folder sitting next to it.

---

### Good to know
- One cell fetches **live weather from the internet**. If you're offline, no
  problem — it automatically uses a saved copy.
- Look for cells marked **`# TODO`** — those are the bits you finish. Replace the
  `...` with your code, then run the cell. Stuck? Ask!
