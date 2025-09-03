// Interface-based Media Player

interface Playable {
    void play();
    void pause();
    void stop();
}

// MP3Player implementing Playable interface
class MP3Player implements Playable {
    public void play() {
        System.out.println("Playing MP3 audio...");
    }
    public void pause() {
        System.out.println("Pausing MP3 audio...");
    }
    public void stop() {
        System.out.println("Stopping MP3 audio...");
    }
}

// VideoPlayer implementing Playable interface
class VideoPlayer implements Playable {
    public void play() {
        System.out.println("Playing video...");
    }
    public void pause() {
        System.out.println("Pausing video...");
    }
    public void stop() {
        System.out.println("Stopping video...");
    }
}

// Main class
public class MediaPlayerDemo {
    public static void main(String[] args) {
        // MP3 Player
        Playable mp3 = new MP3Player();
        mp3.play();
        mp3.pause();
        mp3.stop();

        System.out.println("------------------------");

        // Video Player
        Playable video = new VideoPlayer();
        video.play();
        video.pause();
        video.stop();
    }
}
