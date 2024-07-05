# resetDarktable
reset darktable collections (stop locking up looking for offloaded files, dangit)

macOS:
remove lines from [user]/.config/darktable/darktablerc matching 'import_last_place', 'import_custom_places', 'import_last_dire'
