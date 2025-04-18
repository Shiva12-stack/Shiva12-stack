-import React from "react";

export default function Resume() { return ( <div className="min-h-screen bg-gray-100 text-gray-800 p-6"> <div className="max-w-3xl mx-auto bg-white rounded-2xl shadow-lg p-8"> <h1 className="text-4xl font-bold text-center mb-2">D Shivadeep</h1> <p className="text-center text-gray-600 mb-4">B.Tech Fresher</p> <div className="text-center text-sm mb-6"> <p>Hyderabad</p> <p>123456789 | anything@email.com</p> <div className="flex justify-center gap-4 mt-2"> <a href="#" className="text-blue-500">GitHub</a> <a href="#" className="text-blue-500">LinkedIn</a> </div> </div>

<section className="mb-6">
      <h2 className="text-xl font-semibold mb-2">About Me</h2>
      <p>
        I'm Shivadeep, a B.Tech graduate from St. Mary’s College with a passion
        for software development and continuous learning. I am eager to kickstart
        my career in tech and contribute meaningfully to innovative projects.
      </p>
    </section>

    <section className="mb-6">
      <h2 className="text-xl font-semibold mb-2">Skills</h2>
      <ul className="list-disc list-inside">
        <li>Python</li>
        <li>Java</li>
        <li>HTML</li>
        <li>SQL</li>
        <li>Git & Version Control</li>
        <li>Problem Solving</li>
      </ul>
    </section>

    <section className="mb-6">
      <h2 className="text-xl font-semibold mb-2">Education</h2>
      <p className="font-medium">B.Tech - St. Mary’s College</p>
      <p className="text-sm text-gray-600">Expected Graduation: 2025</p>
    </section>

    <section>
      <h2 className="text-xl font-semibold mb-2">Projects</h2>
      <p className="text-sm text-gray-500 italic">No projects added yet.</p>
    </section>
  </div>
</div>

); }

