# linux-ec2-scripta

find /home/ec2-user/  -type f -name "*.mov"  Search files with 'mov' extension
find . -iname "*.mov" -exec basename {} .mov ';' View file without extension.
find . -type f \( -name "*.mp4" \) Search a file with a specific extension
ffmpeg -i tmp/video1.mov tmp/video1.mp4  Convert video1.mov to video1.mp4
