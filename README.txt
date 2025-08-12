SwipePlaces Tbilisi v6.4

What changed
- Open now quick chip
- Haptics setting, used on shortlist and media delete
- Share calendar uses shareFiles to avoid type issues
- Clear cache and clear media actions in Settings
- Same modern UI and flows as v6.3

Run
1. flutter pub get
2. flutter create .
3. Add Google Places key in lib/src/services/places_repository.dart
4. Android, add Maps key and location permissions
5. iOS, add Info.plist privacy strings
6. flutter run
