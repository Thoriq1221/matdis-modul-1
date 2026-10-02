## AND - MAU MAIN KELUAR
| No | sudah_mandi | sudah_makan | sudah_izin | hasil | Output |
|----|-------------|-------------|------------|-------|--------|
| 1  | True        | True        | True       | True  | GAS MAIN KELUAR |
| 2  | True        | True        | False      | False | BELUM BOLEH KELUAR |
| 3  | True        | False       | True       | False | BELUM BOLEH KELUAR |
| 4  | False       | True        | True       | False | BELUM BOLEH KELUAR |

## AND - MAU TIDUR
| No | sudah_belajar | tugas_selesai | alarm_sudah_aktif | hasil | Output |
|----|---------------|---------------|-------------------|-------|--------|
| 1  | True          | True          | True              | True  | GAS TIDUR |
| 2  | True          | True          | False             | False | BELUM BISA TIDUR TENANG |
| 3  | True          | False         | True              | False | BELUM BISA TIDUR TENANG |
| 4  | False         | True          | True              | False | BELUM BISA TIDUR TENANG |

## AND - MAU PERGI KULIAH
| No | sudah_mandi | sudah_sarapan | tas_sudah_dibawa | hasil | Output |
|----|-------------|---------------|------------------|-------|--------|
| 1  | True        | True          | True             | True  | GAS BERANGKAT KULIAH |
| 2  | True        | True          | False            | False | WOI, ADA YANG BELUM SIAP |
| 3  | True        | False         | True             | False | WOI, ADA YANG BELUM SIAP |
| 4  | False       | True          | True             | False | WOI, ADA YANG BELUM SIAP |

## OR - CARI ALASAN NGGAK KELUAR
| No | hujan | lagi_mager | dompet_tipis | hasil | Output |
|----|-------|------------|--------------|-------|--------|
| 1  | True  | False      | False        | True  | MENDING DI RUMAH AJA |
| 2  | False | True       | False        | True  | MENDING DI RUMAH AJA |
| 3  | False | False      | True         | True  | MENDING DI RUMAH AJA |
| 4  | False | False      | False        | False | GAS KELUAR |

## OR - BOLEH ISTIRAHAT
| No | tugas_selesai | kuliah_libur | dosen_batal | hasil | Output |
|----|---------------|--------------|-------------|-------|--------|
| 1  | True          | False        | False       | True  | GAS REBAHAN |
| 2  | False         | True         | False       | True  | GAS REBAHAN |
| 3  | False         | False        | True        | True  | GAS REBAHAN |
| 4  | False         | False        | False       | False | MASIH ADA URUSAN |

## OR - MAU BELI MAKANAN
| No | lapar | uang_ada | ada_promo | hasil | Output |
|----|-------|----------|-----------|-------|--------|
| 1  | True  | False    | False     | True  | WAKTUNYA CARI MAKAN |
| 2  | False | True     | False     | True  | WAKTUNYA CARI MAKAN |
| 3  | False | False    | True      | True  | WAKTUNYA CARI MAKAN |
| 4  | False | False    | False     | False | NANTI AJA MAKANNYA |

## XOR - NAIK MOTOR ATAU JALAN KAKI
| No | naik_motor | jalan_kaki | hasil | Output |
|----|------------|------------|-------|--------|
| 1  | True       | False      | True  | OKE, BERANGKAT |
| 2  | False      | True       | True  | OKE, BERANGKAT |
| 3  | True       | True       | False | PILIH SALAH SATU DULU |
| 4  | False      | False      | False | PILIH SALAH SATU DULU |

## XOR - PILIH NONTON ATAU BELAJAR
| No | nonton | belajar | hasil | Output |
|----|--------|---------|-------|--------|
| 1  | True   | False   | True  | OKE, SATU DULU |
| 2  | False  | True    | True  | OKE, SATU DULU |
| 3  | True   | True    | False | JANGAN DUA-DUANYA, FOKUS! |
| 4  | False  | False   | False | JANGAN DUA-DUANYA, FOKUS! |
