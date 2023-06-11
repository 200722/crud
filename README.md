# Login & Registration + UPLOAD + Edit + Delete Picture FIn PHP And MySQL

## TECHNOLOGIES

1. PHP
1. MYSQL
1. BOOTSTRAP 5
1. HTML
1. CSS
   //database
   -- phpMyAdmin SQL Dump
   -- version 5.2.1
   -- https://www.phpmyadmin.net/
   --
   -- Host: 127.0.0.1
   -- Gegenereerd op: 11 jun 2023 om 22:35
   -- Serverversie: 10.4.28-MariaDB
   -- PHP-versie: 8.2.4

SET SQL_MODE = "NO_AUTO_VALUE_ON_ZERO";
START TRANSACTION;
SET time_zone = "+00:00";

/_!40101 SET @OLD_CHARACTER_SET_CLIENT=@@CHARACTER_SET_CLIENT _/;
/_!40101 SET @OLD_CHARACTER_SET_RESULTS=@@CHARACTER_SET_RESULTS _/;
/_!40101 SET @OLD_COLLATION_CONNECTION=@@COLLATION_CONNECTION _/;
/_!40101 SET NAMES utf8mb4 _/;

--
-- Database: `pvb`
--

---

--
-- Tabelstructuur voor tabel `course`
--

CREATE TABLE `course` (
`id` int(11) NOT NULL,
`fname` varchar(255) NOT NULL,
`text` varchar(255) NOT NULL,
`username` text NOT NULL,
`password` varchar(255) NOT NULL,
`pp` varchar(255) NOT NULL DEFAULT 'default-pp.png'
) ENGINE=InnoDB DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_general_ci;

--
-- Gegevens worden geëxporteerd voor tabel `course`
--

INSERT INTO `course` (`id`, `fname`, `text`, `username`, `password`, `pp`) VALUES
(1, 'k', '', 'k', '$2y$10$EuJ6GOkXEgBT2AkT5awKQegmZCHtDEG6iRSd.H5f7/VAKWnTW/Rsi', 'k6483f2dcbe5df0.81574134.jpeg'),
(2, 'Reem', '', 'reem rafghad mmmm', '$2y$10$xM1Y5cJ6sI9KInJ6ggZacuT2dOnc9VfP67O6BalEIKaEPNu3QPAs2', 'reem rafghad mmmm64857a1c773101.56387182.jpeg'),
(3, 'r', '', 'r', '$2y$10$DeN7l1dOGRDM50tnIIsVkOnBepD4IgT37iHNARsFeslPXoT4bsD3a', 'r64857a58ba9e39.95766990.jpeg'),
(4, 'm', '', 'r', '$2y$10$v4JXaXQa2DV1PUwT6MrqfeCDtyr.Y6cV/uig/KhlmGiNA.ZsiGSuu', 'default-pp.png'),
(5, 'mm', '', 'lll', '$2y$10$/ZisRO7EdjddC4t9AohAmOboD4Csz8Pa1IVkH/rRv.VkMdWgeMJlW', 'lll64857b096f41c7.74024222.jpeg'),
(6, 'ee', '', 'r', '$2y$10$j/Vfz4xj3SVhdhpBcHgttO08cge23bJbnGg.LoCt6c8I3gvdHg1nG', 'r64859756714291.47943628.jpeg'),
(7, 'e', '', 'rr', '$2y$10$PLc8VpuXmraxrr/jh6JCE..3AagcNzDlaAVaD7KCyNdpuTULk9d7q', 'rr648597793e91d0.63607805.jpeg'),
(8, 'r', 'hhhh', 'e', '$2y$10$6xR7qC/Wk4vV/LDKUg.SmODgsi2Xtj3o3gHbbh/Ye41fkCHzxy2.C', 'e64859b36cce480.01890489.jpeg'),
(9, 'eeeeeeeeeeee', 'eeeeeeeeeeeeeeeeeeeeeee', 'w', '$2y$10$azIgijr2OcTXoxafGZjq7OAnIHgxJdSgUjacajp7fxZFJwuGyoiNS', 'w6485b85697f230.12012756.jpeg'),
(10, 'ff', 'ff', 'reem', '$2y$10$66tEqjCFfTM2v1XgnofyheXqrDyaxKeZYl3wXaCdMgvOc0MvW2wn2', 'reem64862fff87a7d5.33115452.jpeg');

--
-- Indexen voor geëxporteerde tabellen
--

--
-- Indexen voor tabel `course`
--
ALTER TABLE `course`
ADD PRIMARY KEY (`id`);

--
-- AUTO_INCREMENT voor geëxporteerde tabellen
--

--
-- AUTO_INCREMENT voor een tabel `course`
--
ALTER TABLE `course`
MODIFY `id` int(11) NOT NULL AUTO_INCREMENT, AUTO_INCREMENT=11;
COMMIT;

/_!40101 SET CHARACTER_SET_CLIENT=@OLD_CHARACTER_SET_CLIENT _/;
/_!40101 SET CHARACTER_SET_RESULTS=@OLD_CHARACTER_SET_RESULTS _/;
/_!40101 SET COLLATION_CONNECTION=@OLD_COLLATION_CONNECTION _/;
