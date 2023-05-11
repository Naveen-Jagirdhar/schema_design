# Design Database Schema for a system like Netflix with the following Use Cases.

<h5>Usecase</h5>
  <li>Netflix has users</li>
  <li>Every user has an email and a password</li>
  <li>Users can create profiles to have separate independent environments.</li>
  <li>Each profile has a name and a type. Type can be KID or ADULT.</li>
  <li>There are multiple videos on Netflix.</li>
  <li>For each video, there will be a title, description and a cast.</li>
  <li>A cast is a list of actors who were a part of the video. For each actor, we need to know their name and list of videos they were a part of.</li>
  <li>For every video, for any profile who watched that video, we need to know the status (COMPLETED/ IN PROGRESS).</li>
  <li>For every profile for whom a video is in progress, we want to know their last watch timestamp.</li>