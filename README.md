- Captain naqel is website that have a colection of school and collage drivers, so the students can use the website to explore and choose a trip from and to the school or collage, in other hand the school drivers can register in the website and offer their trips.




- The entities and methods that daveloped by Abdulaziz Alshehri:
  
    - Entities:
            - Captain
            - Compiant
            - Parent
            - ParentRequestRide
            - RequestRide
            - SuccessorStudent

      - Methods:
            -| AdminService: displayAllComplaints();
            -| AdminService: makeWarnToCaptain();
            -| CaptainService: displayRequestRides();
            -| CaptainService: ApproveRequestRide();
            -| CaptainService: ApproveParentRequestRide();
            -| CaptainService: displayParentRequestRides();
            -| ParentService: addStudentToParent();
            -| ParentService: addRequestRideByParent();
            -| ParentService: displayCaptainsTrip();
            -| ParentService: joinDailyTrip();
            -| StudentService: ReportAllStudent();
            -| StudentService: requestRide();
            -| StudentService: cancelRequestStudent();
            -| StudentService: makeCompliant();
            -| StudentService: displayCaptainsTrip();
