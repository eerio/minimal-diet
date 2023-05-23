
I recommend putting this into your `~/.bash_aliases`:
alias venv=". .venv/bin/activate"
If not, you'll have to activate the venv manually each time;
after changing your `~/.bash_aliases` file, you may need to
re-load it in your terminal by `. ~/.bashrc`

You may need python >= 3.7 to run the scripts in this repo (I tested with python 3.10, but the differences here should be minor)

First, create yourself a virtual environment. Run these commands in the root
folder of this repo:
python3 -m venv .venv
Activate the venv using the alias created above, manually otherwise
venv
Upgrade pip, install the requirements and start the Jupyter Notebook server
pip install --upgrade pip
pip install -r requirements.txt
jupyter notebook

You can safely ignore the warning displayed by the Jupyter Notebook UI:
Read the migration plan to Notebook 7 to learn about the new features
  and the actions to take if you are using extensions[...]
Because it's about an update to Jupyter Notebook, which isn't even released 
yet

To install something without restarting the Jupter kernel, e.g. for
pandas run:
!pip install pandas
in a new cell in some notebook;
don't forget to add the library installed to requirements.txt
(unless it's only for you and not useful for others)

- jaki ryż najlepszy?
  + sam biały jest średni; lepiej wybrać czerwony lub czarny
  + co z metalami ciezkimi w ryzu?
  + nie rozgotowywać ryżu - to prowadzi do przyśpieszenia wchłanialności
- jak się przelicza indeks glikemiczny na to ile trzyma sytość?
- jaki olej najlepszy?
  + olej rzepakowy w polsce chyba najlepszy - dużo zdrowszy niż oliwa,
    wyższy punkt dymienia, mniej tłuszczy nasyconych (x2), więcej witaminy
    E (x4)

-2000 kcal dziennie
-10% energii z białka (Oxford handbook of nutrition and dietetics 3e)
-max 30g białka na raz
-ok. 55g białka dziennie, let's say 60g

-co monitorować?:
  -protein
  -energy
  -vitamin B12
  -vitamin D
  -calcium
  -iron
  -zinc
-protein complementing foods must be consumed on the same day,
  but not necessarily at the same meal!! (p. 374 pdfa)


ciężko dokładnie z tymi aminokwasami; trzeba jeść grain + pulse po prostu

fajna praca:
https://www.mdpi.com/2304-8158/12/7/1383/pdf
