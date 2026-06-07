# Steam-Sync-Manager

Steam Sync Manager helps you generate and manage Steam launch options for game save data through rclone. This is intended for games that do not have native Steam Cloud Save functionality.

The application can:
- Detect Steam user profiles
- Discover configured rclone remotes
- Generated launch option commands automatically

### Launch Option Generation
Generate launch options such as:

```bash
rclone copy remote:path local/path --update ; %command% ; rclone sync local/path remote:path
```

## Requirements
- Linux
- Python 3.10+
- GTK 3
- rclone
- Steam

## Installation

Clone the repository:

```bash
git clone https://github.com/AdamHadouTemsamani/Steam-Sync-Manager.git
cd Steam-Sync-Manager
```

Install dependencies:

```bash
pip install -r requirements.txt
```
Run:

```bash
python steam_sync_manager.py
```
## License

Apache 2.0 Licence

