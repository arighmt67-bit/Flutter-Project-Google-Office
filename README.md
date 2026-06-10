# Flutter Google Office App

A Flutter application built as the final project for the 
**"Belajar Membuat Aplikasi Flutter untuk Pemula"** course on Dicoding.

## 📋 Project Overview
This app displays a list of Google offices around the world, 
with search functionality and detailed office information.

## ✅ Reviewer Assessment
All 3 submission criteria achieved at **Advanced level (4/4 pts each)**:
- ✅ Google Office List Page — Advanced
- ✅ Google Office Detail Page — Advanced
- ✅ Navigation & Data Passing — Advanced

## 🚀 Features
- **Home Page**: Searchable list of 10 Google offices (filter by name or address)
- **Responsive Layout**: ListView on mobile, GridView on screens wider than 700px
- **Detail Page**: Full office info including address, phone, region, 
  latitude & longitude
- **Smooth Navigation**: Bottom-to-top slide transition using PageRouteBuilder
- **Material 3 Design**: Google-brand color palette with custom design tokens

## 🛠️ Tech Stack
- Flutter (Material 3)
- Dart SDK ^3.10.1
- State management: StatefulWidget + setState
- Font: Georgia (system font)
- No external UI packages required

## 📁 Project Structure
lib/
├── main.dart
├── app.dart
├── model/
│   └── google_office.dart   # Data model & 10 office entries
└── view/
    ├── home_page.dart        # List/Grid with search
    └── detail_page.dart      # Office detail view

## 🏃 How to Run
1. Clone this repository
2. Run `flutter pub get`
3. Run `flutter run`

## 📱 Screenshots
_Coming soon_

## 🎓 Course
[Belajar Membuat Aplikasi Flutter untuk Pemula — Dicoding](https://www.dicoding.com)
