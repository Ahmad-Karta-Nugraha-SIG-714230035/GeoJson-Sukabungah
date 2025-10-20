# GIS-Ahmad-Karta-Nugraha


# 🗺️ GeoJSON Jalan di Kelurahan Sukabungah, Kecamatan Sukajadi, Kota Bandung

## 📍 Deskripsi
Repositori ini berisi data **ruas jalan di sekitar Kelurahan Sukabungah**, Kecamatan Sukajadi, Kota Bandung, dalam format **GeoJSON (LineString)**.  
Data dibuat berdasarkan hasil digitasi manual dari peta di [geojson.io](https://geojson.io) untuk keperluan tugas pemetaan digital.

Terdapat **6 ruas jalan** yang digambarkan di area Sukabungah dan sekitarnya.

---

## 🧭 Struktur Data
Setiap jalan direpresentasikan sebagai satu fitur (`Feature`) dalam koleksi (`FeatureCollection`), dengan struktur:

```json
{
  "type": "Feature",
  "properties": {
    "nama_jalan": "Jl. Sukabungah"
  },
  "geometry": {
    "type": "LineString",
    "coordinates": [
      [107.5973, -6.8930],
      [107.5956, -6.8928]
    ]
  }
}
```
<h1>Disimpan di mongoDB</h1>
<img width="1345" height="484" alt="image" src="https://github.com/user-attachments/assets/764f75ad-7735-467d-8141-f024f4397c87" />
<img width="1345" height="488" alt="image" src="https://github.com/user-attachments/assets/34087e6c-9d00-4d64-abff-1cd271bcd9a1" />

