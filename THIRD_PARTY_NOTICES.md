# Third-Party Notices

13SoulMU Student includes or invokes third-party software distributed under
separate licenses. Those licenses apply only to their respective components
and do not change the proprietary license of 13SoulMU Student.

## FFmpeg

The Windows package includes separate `ffmpeg.exe` and `ffprobe.exe` command
line programs. FFmpeg is licensed under the GNU Lesser General Public License
(LGPL) version 2.1 or later; builds configured with GPL components are licensed
under the GNU General Public License (GPL) version 2 or later. The `ffmpeg.exe`
shipped in version 2.0.3 is the Gyan.dev 6.1.1 essentials build and reports
`--enable-gpl --enable-version3`; it is therefore distributed under GPLv3.

- Project: https://ffmpeg.org/
- Distributed build: https://github.com/GyanD/codexffmpeg/releases/tag/6.1.1
- FFmpeg 6.1.1 source: https://ffmpeg.org/releases/ffmpeg-6.1.1.tar.xz
- Gyan.dev build recipes: https://github.com/GyanD/codexffmpeg/tree/6.1.1
- BtbN build recipes used for `ffprobe.exe`: https://github.com/BtbN/FFmpeg-Builds
- License information: https://ffmpeg.org/legal.html
- GPLv3 text: https://www.gnu.org/licenses/gpl-3.0.txt

FFmpeg is run as a separate process. No FFmpeg source code is incorporated into
the proprietary 13SoulMU Student application.

For at least three years after the release of version 2.0.3, the distributor
will provide a copy of the complete corresponding source available for the
bundled GPL/LGPL command-line components upon request, for no more than the
reasonable cost of providing that copy. Contact isan@poofone.com.tw.

## whisper.cpp

Offline speech recognition uses whisper.cpp, distributed under the MIT License.

- Project and source: https://github.com/ggerganov/whisper.cpp
- License: https://github.com/ggerganov/whisper.cpp/blob/master/LICENSE

## OpenAI Whisper model

The bundled Whisper base model originates from the OpenAI Whisper project and
is distributed under the MIT License.

- Project and source: https://github.com/openai/whisper
- License: https://github.com/openai/whisper/blob/main/LICENSE

Complete copyright and license texts included in the installed package remain
authoritative.
