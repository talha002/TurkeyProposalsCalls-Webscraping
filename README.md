# Webscrapin Algorithm of Project Proposal Calls In Turkey

Hello every one,

I built this algorithm to collect data of project proposal calls In Turkey. It is a simple webscarping algorithm. 

In **first step** (first code cell) I collect data from **"https://yatirimadestek.gov.tr"**. This website has a general table which includes national project propsal calls from various instutions.

In **second step** (second code cell) I collect data from **"https://uidb-pbs.tubitak.gov.tr"** this web site includes TUBITAK's international projecect proposal calls.

In **third step** (third code cell) I collect data from **"https://hibeler.ab.gov.tr"** and this website includes EU's international project proposal calls.

In **fourth and fifth step** (fourth and fifth cell) I make a dataframe from collected data and tranform it to an excel table.

In excel table there is four column header which are named as "Kurum Adı", "Program Adı", "Çağrı Durumu", "Son Başvuru Tarihi".

**"Program adı"** means name of the project program call

**"Kurum adı"** means name of instution which opening the call.

**"Çağrı Durumu"** means statute of the call, whether is it active (open) or closed.

**"Son Başvuru Tarihi"** means deadline for apply to the call.
