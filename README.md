![Logo](https://github.com/user-attachments/assets/183a3d07-731c-4009-8432-33424ae85cf5)

# Tashkelah ⚽

Tashkelah is a community-driven sports booking platform built as a final project for the Tuwaiq Academy Java Bootcamp. It enables players to join matches solo or with friends, and allows organizers to manage sports fields, create matches, and coordinate bookings — all through a structured, role-based system.

---

## 🚀 Features

- Player registration and team creation (solo or with friends)
- Organizer registration and field management (after admin approval)
- Private match flow for friends
- Public match flow for solo players
- Match filtering by sport and location
- Booking system with price split per player
- Payment integration via Moyasar
- Email and WhatsApp notifications
- Admin management and monitoring capabilities

---

## 🛠️ Technologies Used

- Java
- Spring Boot
- Spring Security
- JPA & Hibernate
- MySQL
- RESTful APIs
- Lombok
- Maven
- Moyasar API (payment gateway)
- JavaMailSender (email)
- WhatsApp API (Twilio or custom)

## 📊 Architecture Diagrams

### 🔷 Class Diagram
> ![Class Diagram](https://github.com/user-attachments/assets/34b72330-2fcf-44b2-9601-23ca824e6516)


### 🔶 Use Case Diagram
> ![Use Case Diagram](https://github.com/user-attachments/assets/28508414-0733-4256-9e8c-9f1bf774dceb)


---

## 📬 API Documentation

- 🔗 [Postman Documentation](https://documenter.getpostman.com/view/42844638/2sB2qUmPwG)
- Base URL: `http://tuwaiq-app-env.eba-9nhuvpa3.eu-central-1.elasticbeanstalk.com`

---

## 🎨 Figma Design

- 🔗 [View UI on Figma](https://www.figma.com/design/3wzDvkE6kbXGBVgeGu4lnF/%D8%AA%D8%B4%D9%83%D9%8A%D9%84%D8%A9?node-id=9-2&p=f&t=T7G5n1vvnv9yWZfH-0)

---

## 🧰 Endpoints Table

| #  | Endpoint Description                   | Creator |
|----|----------------------------------------|---------|
| 13 | Get player's public match bookings     | Eatzaz  |
| 24 | Register player                        | Eatzaz  |
| 25 | Show details stadiums by sport type    | Eatzaz  |
| 28 | Play with a public match               | Eatzaz  |
| 29 | Get public matches                     | Eatzaz  |
| 30 | Get teams for public match             | Eatzaz  |
| 32 | Show player selections                 | Eatzaz  |
| 33 | Notify when payment completed          | Eatzaz  |
| 34 | Change match status after full         | Eatzaz  |
| 35 | Public match payment                   | Eatzaz  |
| 36 | Book public match                      | Eatzaz  |
| 59 | Show fields by sport and address       | Eatzaz  |
| 59  | Show fields by sport and address       | Eatzaz  |
| 60  | Add a rating to the field              | Eatzaz  |
| 61  | Get reviews by field                   | Eatzaz  |
| 62  | Delete review                          | Eatzaz  |
| 63  | Update review                          | Eatzaz  |
