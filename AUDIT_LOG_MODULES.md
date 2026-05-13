# Audit Log Modules

This inventory lists source modules that create audit logs, expose audit log APIs, send audit actor metadata, or call the shared audit event endpoint. Files are sorted by project tree.

## Backend

### Root

- `backend/server.js`

### Utilities

- `backend/utils/auditLogger.js`
- `backend/utils/registerSocketHandlers.js`

### Admin Routes

- `backend/routes/admin_routes/registrarRoute.js`
- `backend/routes/admin_routes/signature.js`

### Admission Routes

- `backend/routes/admission_routes/QualifyingInterviewExam.js`
- `backend/routes/admission_routes/applicantScoringRoute.js`
- `backend/routes/admission_routes/entranceExamSchedule.js`
- `backend/routes/admission_routes/interviewQualifyingRoute.js`
- `backend/routes/admission_routes/subjectsRoute.js`
- `backend/routes/admission_routes/verifyDocumentSchedule.js`

### Applicant Routes

- `backend/routes/applicant_routes/applicantFormRoute.js`

### Auth Routes

- `backend/routes/auth_routes/accessRoute.js`
- `backend/routes/auth_routes/authRoutes.js`
- `backend/routes/auth_routes/changePassword.js`
- `backend/routes/auth_routes/userPageAccessRoute.js`

### Faculty Routes

- `backend/routes/faculty_routes/facultyDegree.js`
- `backend/routes/faculty_routes/facultyRoute.js`

### Payment Routes

- `backend/routes/payment/feeRules.js`
- `backend/routes/payment/matriculation.js`
- `backend/routes/payment/receiptCounter.js`

### Reset Password Routes

- `backend/routes/reset_password_routes/applicantresetpasswordRoutes.js`
- `backend/routes/reset_password_routes/facultyresetpasswordRoutes.js`
- `backend/routes/reset_password_routes/registrarresetpasswordRoutes.js`
- `backend/routes/reset_password_routes/studentresetpasswordRoutes.js`

### Student Routes

- `backend/routes/student_routes/registerStudent.js`
- `backend/routes/student_routes/studentAccounts.js`

### System Routes

- `backend/routes/system_routes/announcement.js`
- `backend/routes/system_routes/auditLogsRoute.js`
- `backend/routes/system_routes/coursePanelRoute.js`
- `backend/routes/system_routes/courseTagging.js`
- `backend/routes/system_routes/curriculumRoute.js`
- `backend/routes/system_routes/departmentRoom.js`
- `backend/routes/system_routes/departmentSection.js`
- `backend/routes/system_routes/departmentSectionTagging.js`
- `backend/routes/system_routes/dprmntRoute.js`
- `backend/routes/system_routes/dprtmntCurriculum.js`
- `backend/routes/system_routes/emailTemplate.js`
- `backend/routes/system_routes/evaluation.js`
- `backend/routes/system_routes/nstpTagging.js`
- `backend/routes/system_routes/paymentExportingRoute.js`
- `backend/routes/system_routes/programRoute.js`
- `backend/routes/system_routes/programSlots.js`
- `backend/routes/system_routes/programTaggingRoute.js`
- `backend/routes/system_routes/requirementsRoute.js`
- `backend/routes/system_routes/roomRegistrationRoute.js`
- `backend/routes/system_routes/schoolYear.js`
- `backend/routes/system_routes/settingsRoute.js`
- `backend/routes/system_routes/tosfRoute.js`
- `backend/routes/system_routes/yearLevel.js`

### Other Backend Routes

- `backend/routes/import.js`

## Frontend

### Account Management

- `frontend/src/account_management/ApplicationProcessSuperAdmin.jsx`
- `frontend/src/account_management/ArchivedModule.jsx`
- `frontend/src/account_management/MigrationDataPanel.jsx`
- `frontend/src/account_management/PageCRUD.jsx`
- `frontend/src/account_management/RegisterProf.jsx`
- `frontend/src/account_management/RegisterRegistrar.jsx`
- `frontend/src/account_management/StudentAccounts.jsx`
- `frontend/src/account_management/StudentGradeFile.jsx`
- `frontend/src/account_management/SuperAdminApplicantDashboard1.jsx`
- `frontend/src/account_management/SuperAdminApplicantDashboard2.jsx`
- `frontend/src/account_management/SuperAdminApplicantDashboard3.jsx`
- `frontend/src/account_management/SuperAdminApplicantDashboard4.jsx`
- `frontend/src/account_management/SuperAdminApplicantResetPassword.jsx`
- `frontend/src/account_management/SuperAdminFacultyResetPassword.jsx`
- `frontend/src/account_management/SuperAdminProfessorEducation.jsx`
- `frontend/src/account_management/SuperAdminRegistrarResetPassword.jsx`
- `frontend/src/account_management/SuperAdminRequirementsUploader.jsx`
- `frontend/src/account_management/SuperAdminStudentDashboard1.jsx`
- `frontend/src/account_management/SuperAdminStudentDashboard2.jsx`
- `frontend/src/account_management/SuperAdminStudentDashboard3.jsx`
- `frontend/src/account_management/SuperAdminStudentDashboard4.jsx`
- `frontend/src/account_management/SuperAdminStudentResetPassword.jsx`
- `frontend/src/account_management/UploadEnrolledSubject.jsx`
- `frontend/src/account_management/UserPageAccess.jsx`

### Admission

- `frontend/src/admission/AdminDashboard1.jsx`
- `frontend/src/admission/AnnouncementForAdmission.jsx`
- `frontend/src/admission/ApplicantExamSubjects.jsx`
- `frontend/src/admission/ApplicantScoring.jsx`
- `frontend/src/admission/ApplicationProcessAdmin.jsx`
- `frontend/src/admission/AssignEntranceExam.jsx`
- `frontend/src/admission/AssignScheduleToApplicants.jsx`
- `frontend/src/admission/EvaluatorApplicantList.jsx`
- `frontend/src/admission/ProctorApplicantList.jsx`
- `frontend/src/admission/RoomRegistration.jsx`
- `frontend/src/admission/StudentRequirements.jsx`
- `frontend/src/admission/VerifyDocumentsSchedule.jsx`
- `frontend/src/admission/VerifySchedule.jsx`

### Components

- `frontend/src/components/CORForScholarship.jsx`
- `frontend/src/components/Login.jsx`
- `frontend/src/components/LoginEnrollment.jsx`
- `frontend/src/components/Register.jsx`
- `frontend/src/components/StudentTable.jsx`

### Course Management

- `frontend/src/course_management/CoursePanel.jsx`
- `frontend/src/course_management/CurriculumPanel.jsx`
- `frontend/src/course_management/NSTPTagging.jsx`
- `frontend/src/course_management/ProgramPanel.jsx`
- `frontend/src/course_management/ProgramTagging.jsx`

### Department Management

- `frontend/src/department_management/CollegeScheduleChecker.jsx`
- `frontend/src/department_management/DepartmentCurriculumPanel.jsx`
- `frontend/src/department_management/DepartmentSection.jsx`
- `frontend/src/department_management/DepartmentSectionTagging.jsx`
- `frontend/src/department_management/DprtmntRegistration.jsx`
- `frontend/src/department_management/DprtmntRoom.jsx`
- `frontend/src/department_management/ScheduleChecker.jsx`

### Enrollment Management

- `frontend/src/enrollment_management/AssignQualifyingInterviewExam.jsx`
- `frontend/src/enrollment_management/AssignScheduleToApplicantsQualifyingInterviewer.jsx`
- `frontend/src/enrollment_management/CertificateOfRegistrationForCollege.jsx`
- `frontend/src/enrollment_management/CourseTaggingForCollege.jsx`
- `frontend/src/enrollment_management/CourseTaggingForSummerCollege.jsx`
- `frontend/src/enrollment_management/OfficialRequirements.jsx`
- `frontend/src/enrollment_management/QualifyingInterviewExamScore.jsx`
- `frontend/src/enrollment_management/RegistrarRequirements.jsx`
- `frontend/src/enrollment_management/StudentNumberingPerCollege.jsx`

### Faculty

- `frontend/src/faculty/FacultyEvaluation.jsx`
- `frontend/src/faculty/GradingSheet.jsx`

### Medical Management

- `frontend/src/medical_management/DentalAssessment.jsx`
- `frontend/src/medical_management/MedicalApplicantList.jsx`
- `frontend/src/medical_management/MedicalRequirements.jsx`
- `frontend/src/medical_management/MedicalRequirementsForm.jsx`
- `frontend/src/medical_management/PhysicalNeuroExam.jsx`

### Registrar

- `frontend/src/registrar/CORExportingModule.jsx`
- `frontend/src/registrar/CertificateOfRegistrationForRegistrar.jsx`
- `frontend/src/registrar/CourseTagging.jsx`
- `frontend/src/registrar/CourseTaggingForSummer.jsx`
- `frontend/src/registrar/GradingEvaluationForRegistrar.jsx`
- `frontend/src/registrar/StudentEnrollment.jsx`
- `frontend/src/registrar/StudentNumbering.jsx`
- `frontend/src/registrar/SubmittedDocuments.jsx`
- `frontend/src/registrar/SuperAdminApplicantList.jsx`

### System Management

- `frontend/src/system_management/AdminBranches.jsx`
- `frontend/src/system_management/Announcement.jsx`
- `frontend/src/system_management/AuditLogs.jsx`
- `frontend/src/system_management/ChangeYearGradPer.jsx`
- `frontend/src/system_management/EmailTemplateManager.jsx`
- `frontend/src/system_management/EvaluationCrud.jsx`
- `frontend/src/system_management/GradeConversionAdmin.jsx`
- `frontend/src/system_management/MatriculationPaymentModule.jsx`
- `frontend/src/system_management/PaymentExportingModule.jsx`
- `frontend/src/system_management/ProgramSlotLimit.jsx`
- `frontend/src/system_management/ReceiptCounterAssignment.jsx`
- `frontend/src/system_management/RequirementsForm.jsx`
- `frontend/src/system_management/SchoolYearPanel.jsx`
- `frontend/src/system_management/SectionPanel.jsx`
- `frontend/src/system_management/SemesterPanel.jsx`
- `frontend/src/system_management/Settings.jsx`
- `frontend/src/system_management/SignatureUpload.jsx`
- `frontend/src/system_management/StudentScholarshipList.jsx`
- `frontend/src/system_management/TOSFCrud.jsx`
- `frontend/src/system_management/YearLevelPanel.jsx`
- `frontend/src/system_management/YearPanel.jsx`

### Utilities

- `frontend/src/utils/auditEvents.js`
