### Stroke Prediction API & Web App

Simple web interface and a machine learning API to predict the probability of a stroke based on user-provided health data.

The API expects the following data points:

```py
jenis_kelamin: int
usia: int
riwayat_hipertensi: int
riwayat_penyakit_jantung: int
sudah_menikah: int
berat_badan: int
riwayat_merokok: float
detak_jantung: int
saturasi_oksigen: int
suhu_tubuh: float
tekanan_sistolik: int
tekanan_diastolik: int
model_name: str
```

How to run:
run the api
```bash
cd api
pip install -r req.txt
uvicorn main:app --host 0.0.0.0 --port 8000 --reload
```
If you want web interface, run this in separate terminal:
```bash
cd web
npm i
npm run dev
```
