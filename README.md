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