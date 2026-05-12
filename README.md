```jsx
export default function DPWebsite() {
  return (
    <div className="min-h-screen bg-black text-white font-sans">
      
      {/* Hero Section */}
      <section className="flex flex-col items-center justify-center text-center px-6 py-24 bg-gradient-to-b from-black to-gray-900">
        <h1 className="text-5xl md:text-7xl font-bold text-yellow-400 mb-4">
          DP MEDIA
        </h1>

        <p className="text-lg md:text-2xl text-gray-300 max-w-2xl">
          Video Editing • Gaming • Tech Innovations • Creative Content
        </p>

        <div className="mt-8 flex gap-4 flex-wrap justify-center">
          <button className="bg-yellow-400 text-black px-6 py-3 rounded-2xl font-semibold">
            View Projects
          </button>

          <button className="border border-yellow-400 px-6 py-3 rounded-2xl">
            Contact Me
          </button>
        </div>
      </section>

      {/* About */}
      <section className="px-6 py-20 max-w-5xl mx-auto">
        <h2 className="text-4xl font-bold text-yellow-400 mb-6">
          About Me
        </h2>

        <div className="bg-gray-900 rounded-3xl p-8 shadow-2xl">
          <p className="text-gray-300 text-lg leading-8">
            Hi, I’m Praneeth — creator of DP MEDIA and the YouTube channel
            Np Geming. I love creating tech projects, editing videos,
            gaming content, and innovative DIY ideas using Arduino and electronics.
          </p>
        </div>
      </section>

      {/* Projects */}
      <section className="px-6 py-20 bg-gray-950">
        <div className="max-w-6xl mx-auto">
          <h2 className="text-4xl font-bold text-yellow-400 mb-12 text-center">
            My Projects
          </h2>

          <div className="grid md:grid-cols-3 gap-8">

            <div className="bg-gray-900 rounded-3xl p-6 shadow-xl">
              <h3 className="text-2xl font-semibold text-yellow-300 mb-4">
                Automatic Gas Timer
              </h3>

              <p className="text-gray-400">
                Smart Arduino-based gas safety system using LCD,
                relay, solenoid valve, and buzzer.
              </p>
            </div>

            <div className="bg-gray-900 rounded-3xl p-6 shadow-xl">
              <h3 className="text-2xl font-semibold text-yellow-300 mb-4">
                Summer Cooling Fan
              </h3>

              <p className="text-gray-400">
                DIY low-budget cooling fan project for summer using simple components.
              </p>
            </div>

            <div className="bg-gray-900 rounded-3xl p-6 shadow-xl">
              <h3 className="text-2xl font-semibold text-yellow-300 mb-4">
                YouTube Shorts
              </h3>

              <p className="text-gray-400">
                Creative tech shorts, gaming edits, and innovation videos.
              </p>
            </div>

          </div>
        </div>
      </section>

      {/* YouTube */}
      <section className="px-6 py-20 max-w-5xl mx-auto text-center">
        <h2 className="text-4xl font-bold text-yellow-400 mb-6">
          Np Geming
        </h2>

        <p className="text-gray-300 text-lg mb-8">
          Subscribe for gaming content, tech experiments, DIY projects,
          and creative edits.
        </p>

        <button className="bg-red-600 px-8 py-4 rounded-2xl font-semibold">
          Subscribe on YouTube
        </button>
      </section>

      {/* Contact */}
      <section className="px-6 py-20 bg-gray-950">
        <div className="max-w-4xl mx-auto text-center">

          <h2 className="text-4xl font-bold text-yellow-400 mb-6">
            Contact Me
          </h2>

          <div className="bg-gray-900 rounded-3xl p-8 shadow-2xl">

            <input
              type="text"
              placeholder="Your Name"
              className="w-full mb-4 p-4 rounded-xl bg-black border border-gray-700"
            />

            <input
              type="email"
              placeholder="Your Email"
              className="w-full mb-4 p-4 rounded-xl bg-black border border-gray-700"
            />

            <textarea
              placeholder="Your Message"
              rows="5"
              className="w-full mb-4 p-4 rounded-xl bg-black border border-gray-700"
            ></textarea>

            <button className="bg-yellow-400 text-black px-8 py-4 rounded-2xl font-semibold">
              Send Message
            </button>

          </div>
        </div>
      </section>

      {/* Footer */}
      <footer className="text-center py-8 border-t border-gray-800 text-gray-500">
        © 2026 DP MEDIA • Designed by Praneeth
      </footer>
    </div>
  );
}
```
