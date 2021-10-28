# Food-Order-Application
A Data Modeling and Business Planning Diagrams of system to provide a platform. So that, customer can order their desired food from the menu and close the order.


/*!40101 SET @OLD_CHARACTER_SET_CLIENT=@@CHARACTER_SET_CLIENT */;
/*!40101 SET @OLD_CHARACTER_SET_RESULTS=@@CHARACTER_SET_RESULTS */;
/*!40101 SET @OLD_COLLATION_CONNECTION=@@COLLATION_CONNECTION */;
/*!40101 SET NAMES utf8mb4 */;

--
-- Database: `food_order_application`
--

-- --------------------------------------------------------

--
-- Table structure for table `admin_info`
--

CREATE TABLE `admin_info` (
  `info_id` int(14) NOT NULL,
  `business_name` varchar(30) NOT NULL,
  `description` varchar(120) NOT NULL,
  `contact` varchar(50) NOT NULL,
  `address` varchar(140) NOT NULL
) ENGINE=InnoDB DEFAULT CHARSET=utf8mb4;

-- --------------------------------------------------------
Note - For the rest information refer to the uploaded files.
