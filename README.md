# LAB-6
tangal 13 agustus 2025
# Mengkoneksikan Mikrotik sebagai stasion ke Access Point

![]()

        Mengkoneksikan Mikrotik sebagai station ke access Point ke Access Point :
        1. Koneksi Mikrotik ke AP  
          Konfigurasi Security Wireless  
          Wireless>Security Profiles  
          klik ( + ) General  
          Ceklis semua Authentication Types, Unicast Chipers, Group Chipers,
          untuk nama bebas
          mode : dynamic keys
          WPA Pre-Shared Key : (pin wifi sndiri)  
          WPA2 Pre-Shared Key : (pin wifi sndiri)  
          klik Apply lalu OK
![]()

![]()

      . K2onfigurasi interface wlan1
        pilih Wireless>Interfaces>wlan1
        klik Tab Wireless>Advanced Mode
        Mode: station
        isi Radio Name: RouterBoard-Belajar/nama hospot
        Security Profile: belajar
        klik Scan>Start
        Klik (nama hospot) lalu Connect
        Apply trus ok
